# Caesar_cipher_in_Python

In cryptography is one of the simplest and most widely known encryption techniques. 
It is a type of substitution cipher in which each letter in the plaintext is replaced by a letter some fixed number of positions down the alphabet.

The encryption be represented using modular arithmetic by first transforming the letters into numbers.
Encryption of a letter x by a shift n can be described mathematically as ( n = key, x = number of character)

**E(x) = (x + n) mod26** <br/>
Decryption is performed similarly, <br/>
**D(x) = (x - n) mod26**

**Example**

**Plain text** = Black <br/>
**Key**        = 4 

![image](https://github.com/Ipeky/Caesar_cipher_in_Python/blob/master/img/alphabet.png)

**Cipher text** = Xhwyg


#### References

[Click for more details](https://en.wikipedia.org/wiki/Caesar_cipher)

