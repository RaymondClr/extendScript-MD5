计算给定字符串值的（[hex](https://en.wikipedia.org/wiki/Hexadecimal)-编码）[MD5](https://en.wikipedia.org/wiki/MD5)哈希值：

```
var hash = md5('value') // "2063c1608d6e0baf80249c42e2be5804"
```

计算给定字符串值和密钥的（[hex](https://en.wikipedia.org/wiki/Hexadecimal)-编码）[HMAC](https://en.wikipedia.org/wiki/HMAC)-MD5哈希值：

```
var hash = md5('value', 'key') // "01433efd5f16327ea4b31144572c67f6"
```

计算一个给定字符串值的原始 [MD5](https://en.wikipedia.org/wiki/MD5) 哈希值：

```
var hash = md5('value', null, true)
```

计算给定字符串值和密钥的原始 [HMAC](https://en.wikipedia.org/wiki/HMAC)-MD5 哈希值：

```
var hash = md5('value', 'key', true)
```