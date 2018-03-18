## Security
* **File Encryption & Decryption**
  - This program utilizes the python hazmat cryptography library to encrypt and decrypt user files. The file will first be padded using PKCS7 to make sure the input to our encryption algorithm is the appropriate block size. CBC mode (AES) will then be used to encrypt a file of the user's choice and output a JSON file.
