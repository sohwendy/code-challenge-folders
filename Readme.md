
##1 - simple file differences

identical files
`a.txt, c.txt`


Expected result
```
.../1/archive/d.jpg
.../1/original/b.txt
.../1/original/d.txt
```


## 2 - file and folder differences

Expected result
```
.../2/archive/X/a.txt
.../2/archive/Y/c.txt
.../2/archive/ZZ/d.txt
.../2/original/X/g.txt
.../2/original/Y/c.jpg
.../2/original/ZZ/d.txt
```

## 3 - #2 with file content differences

Expected
```
.../2/archive/X/a.txt
.../2/original/X/a.txt
```
