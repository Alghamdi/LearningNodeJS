# LearningNodeJS


Source code to accompany my book, "Learning Node.JS".  Every once in a while, I'll
update to the latest version of Node.JS and let everybody know if there are any 
changes or updates required to the code (and will make those changes in the source 
tree).

## Errors and Corrections

As devastating as it is to admit, there are a couple of errors in the book.
Those responsible for these egregious violations of editorial process (me)
have been shot.

### Chapter 8

_p176._  At the top of the page, the `.sort("date")` should read `.sort(sort)`

### Chapter 11

_p249._ There are two lines of the format:

```
var data = process.stdXXX.read();
```

These should read:
```
var data = node.stdXXX.read();
```
