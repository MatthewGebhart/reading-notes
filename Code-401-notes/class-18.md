# Class 18 - Cryptography

## Reading

### Encryption, Decryption & Hacking
[Source Credit](https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:online-data-security/xcae6f4a7ff015e7d:data-encryption-techniques/a/encryption-decryption-and-code-cracking)
- Caesar Cipher was invented by Julius Caesar to communicate messages to his allies
- shifts the alphabet over a certain amount and replaces each letter
- three main techniques to crack a cipher
  - Frequency analysis - looks for most popular letters by frequency
  - Known plaintext - knowing part of the original message
  - Brute Force - There are 25 possible shifts, work through them until you get real words
- 3 aspects of data encryption
  - Encryption: scrambling the data according to a secret key (in this case, the alphabet shift).
  - Decryption: recovering the original data from scrambled data by using the secret key.
  - Code cracking: uncovering the original data without knowing the secret, by using a variety of clever techniques.


### Ceasar Cipher
[Source Credit](https://en.wikipedia.org/wiki/Caesar_cipher)
- for frequency analysis code breaking, computers can use the 'chi-squared statistic'


[Source Credit]()

## Videos

### Cryptography Crash Course
[Cryptography Crash Course](https://www.youtube.com/watch?v=jhXCTbFnK8o)
- Caesar Cypher is a "substitution" cypher
- permutation cyphers - uses rows and columns and a different starting place to encrypt a message
- Data Encryption standard invented by IBM was an early software encryption standard (1977) but was able to be brute forced by 1999
- in 2001 Advanced Encryption Standard (AES) was released which used much bigger keys
- Key exchange is an algorithm that allows two computers to agree on a key without ever sending one. 
  - uses one-way function, operations that are easy to do in one direction but hard to reverse
  - each side sends part of a key that is then combined to form the shared decryption key that was never actually sent and can't be intercepted
- symmetric encryption uses the same key on both sides

## Bookmark and review
[Introduction to Cryptography](https://thebestvpn.com/cryptography/)
[How Computers Generate Random Numbers](https://www.howtogeek.com/183051/htg-explains-how-computers-generate-random-numbers/)

## Things I want to know more about
- how modern crackers and brute force methods work(purely for research purposes....)