# sfntwari

Strip TrueType fonts and convert to WOFF for use in web pages using [sfntly](http://code.google.com/p/sfntly/).

Build sfntly:

```
$ ant
```

Example:

```
$ echo ABCDEFG | ./sfntwari Source.ttf Target.woff
```
