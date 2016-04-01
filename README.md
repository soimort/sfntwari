# sfntwari

Use [sfntly](https://github.com/googlei18n/sfntly) to strip TrueType Fonts (TTF) and convert them to Web Open Fonts (WOFF) for use on web pages.

Build sfntly:

```
$ ant
```

Example:

```
$ echo ABCDEFG | ./sfntwari Source.ttf Target.woff
```
