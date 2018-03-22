## Security
* **File Encryption & Decryption**
  - This program utilizes the python hazmat cryptography library to encrypt and decrypt user files. The file will first be padded using PKCS7 to make sure the input to our encryption algorithm is the appropriate block size. CBC mode (AES) will then be used to encrypt a file of the user's choice and output a JSON file containing the ciphertext, encryption key, iv and file extention. A JSON file containing those four things can be read by the program to decrypt the ciphertext.

* **File Encryption & Decryption, Enhanced with RSA encryption**
  - This program is an upgrade to the file encryption decryption program. The program will be enhanced by utilizing RSA encryption to encrypt the CBC mode (AES) encryption key to output the RSA cipher of the key. The RSA public key and private key will be written out to file. The JSON file outputted by the program will contain the ciphertext, RSA cipher of the encryption key, iv and file extention.
