# Computer_Network_Security

## Introduction
AES (Advanced Encryption Standard) has been implemented for 128-bit key. C++ Programming language is used for implementing the algorithm. AES is method for encrypting data using a key that is known only to sender and the receiver. It is a symmetric key encryption algorithm. It was originally called “Rijndael Cipher”.

## Proposed Work:
AES (128-bit key) is a block cipher which encrypts 128 bits of data. This algorithm treats a block of 16 bytes as a matrix. The input text that is longer than 128 bits is broken up into chunks of 128 bits each. After this division of text into different block of 128 bits each, every block is encrypted separately. Consider the situation in which the input text is not a multiple of 16 or is not divisible by block length then Padding’ is done. Padding is a technique in which 0’s are appended to the text so that every block is complete and there is no free space. Padding is done is such a way that the block size is rounded off to the nearest multiple of 16.

## All Steps
1) Key Expansion
2)Byte Substitution
3) Shift rows
4) Mix Column
5) Add Round key

## Results of Implementation:
Test Case 1: 
•	Message in Plaintext: ‘arjunprakash’ 

•	Message in Hex: 61726a756e7072616b617368

•	Key in Plaintext: ‘THISISMYKEYABCDE’ 

•	Key in Hex: 54 48 49 53 49 53 4d 59 4b 45 59 41 42 43 44 45 

• Encrypted message in Hex: CF 81 2B 11 50 3A F6 5E 87 EC 28 21 FD 38 1F 21
