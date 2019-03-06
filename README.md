# PoemGenerator
Marcov Text Generator Based Poem Generator

To use, run poemCreator.py with Python 2.7, with either syntax:

```
python poemCreator.py true 
```
To re-tokenize poems and recreate word map <br />

or

```
python poemCreator.py [lines] [min] [max]
```
To create a poem.

lines: number of lines in output poem. <br />
min: minimum individual line length in poem. <br />
max: maximum individual line length in poem. <br />

Poem lines can span anywhere from min to max number of words, inclusively.

Example call:

```
python poemCreator.py 5 3 6
```

Output:

```
cromwell  hyes  and 
with  heat  for 
the  very  zone 
or  of  a 
growing  for  fame 
```