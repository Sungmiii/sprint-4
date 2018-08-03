# sprint-4
### use-multiple-ternary-operators

Alright I was struggling all tutorials and finished finally :star:

```
function checkSign(num) {
  return (num) ? "negative" : (num) ? "positive" : "zero";
}
```
That was my code before and checkSign(10) returned negative not positve :scream: 

```
function checkSign(num) {
  return (num<0) ? "negative" : (num) ? "positive" : "zero";
}
```
This is my final code(I spent 1hr) and `checkSign(10)` returned **POSITVE**\
but I don't get it why it's working ... 
