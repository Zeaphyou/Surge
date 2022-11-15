# 常用正则

```
(A).(B)        节点名既有 A又有 B
 
(A)|(B)        节点名有 A 或者 B 

^((?!A).)$     节点名不含有 A 

(?!.(A)).(B)   在所有含B节点中，排除含A节点
```

在线正则训练：[https://regex101.com/r/1paXsy/1](https://regex101.com/r/1paXsy/1)
