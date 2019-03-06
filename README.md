# PoemGenerator
Marcov Text Generator Based Poem Generator

To use, run poemCreator.py with Python 2.7, with either syntax:

```bash
python poemCreator.py true 
```
To re-tokenize poems and recreate word map__

or

```bash
python poemCreator.py [lines] [min] [max]
```
To create a poem.

lines: number of lines in output poem. __
min: minimum individual line length in poem. __
max: maximum individual line length in poem. __

Poem lines can span anywhere from min to max number of words, inclusively.

Example call:

```bash
python poemCreator.py 5 3 6
```

Output:

```bash
cromwell  hyes  and 
with  heat  for 
the  very  zone 
or  of  a 
growing  for  fame 
```