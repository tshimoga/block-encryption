# block-encryption
There are two files that perform specific tasks

1. encrypt.c

2. decrypt.c

encrypt.c:
- The 32 bit block encryption algorithm takes a file as argument and encrypts it. 
- A key is printed to the stdout which will be required while decrypting the file.
- Key is entropy generated and random sampled.

decrypt.c
- Takes as input the key and decrypts the encrypted file.
