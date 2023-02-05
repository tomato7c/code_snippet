集合reduce
```
json.parseText(son).inject(0) { res, v -> res + v.totalAmount.toLong()}
```