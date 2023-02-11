集合reduce
```groovy
json.parseText(son).inject(0) { res, v -> res + v.totalAmount.toLong()}
```