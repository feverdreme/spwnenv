# spwnenv

A spwn utility library to get enviornment variables. To use, just do 

```
env = import spwnenv
```

with a `.env` file in your current working directory. It will return an array of string-pairs. If the `.env` file was like

```
key = FIENOIWNNINNG2j390j0j9
pass= 2401249192
```

then the output will be 

```python
[
    ['key', 'FIENOIWNNINNG2j390j0j9'],
    ['pass', '2401249192']
]
```

This library automatically trims whitespace.