# bs58audaxcheck

[![NPM Package](https://img.shields.io/npm/v/bs58audaxcheck.svg?style=flat-square)](https://www.npmjs.org/package/bs58audaxcheck)


A straight forward implementation of base58check extending upon bs58 for Audax


## Example

```javascript
var bs58audaxcheck = require('bs58audaxcheck')

var decoded = bs58audaxcheck.decode('VMcAbMfj44MqqL1rL4cwxTe8NfgcbAGJUhaXb4rNVqKWpNhf4Za6')

console.log(decoded)
// => <Buffer bf ae c5 39 7b 66 d8 86 31 10 bf 6a 84 22 91 43 19 79 96 b2 46 cc 50 24 1d 70 5b 3b b9 5d 97 4e 41 01>

console.log(bs58audaxcheck.encode(decoded))
// => VMcAbMfj44MqqL1rL4cwxTe8NfgcbAGJUhaXb4rNVqKWpNhf4Za6
```


## LICENSE [MIT](LICENSE)
