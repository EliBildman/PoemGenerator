# PoemGenerator
Marcov Text Generator Based Poem Generator

To use, run poemCreator.py with Python 2.7, with either syntax:

```bash
python poemCreator.py true 
```
to re-tokenize poems and recreate word map

```bash
python poemCreator.py [lines] [min] [max]
```
to create a poem.

lines: number of lines in output poem.
min: minimum individual line length in poem
max: maximum individual line length in poem

Poem lines can span anywhere from min to max number of words, inclusively.

Example call:

```bash
python poemCreator.py 5 3 6
```

output:

```bash
cromwell  hyes  and 
with  heat  for 
the  very  zone 
or  of  a 
growing  for  fame 
```