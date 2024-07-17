
# Image Encryption 

## Overview

This project focuses on encrypting and decrypting images using AES (Advanced Encryption Standard)]. The goal is to demonstrate how images can be securely transmitted and stored using encryption techniques.

## Features  
Encryption: Encrypts images using a chosen encryption algorithm.
Decryption: Decrypts encrypted images back to their original form.
File Support: Supports common image formats (e.g., PNG, JPEG).
Installation
Clone the repository:

```                  bash                           ```

git clone https://github.com/THANU2206/image-encryption.git  
cd image-encryption  

## Install dependencies:


pip install -r requirements.txt     
Usage  
Encrypting an Image
To encrypt an image, run:

css

python encrypt.py 
--input path/to/input_image.jpg
--output path/to/output_encrypted_image.jpg
--key your_encryption_key
Replace path/to/input_image.jpg with the path to the image you want to encrypt, path/to/output_encrypted_image.jpg with the desired output path for the encrypted image, and your_encryption_key with your chosen encryption key.    

Decrypting an Image
To decrypt an encrypted image, run:

css
Copy code
python decrypt.py --input path/to/encrypted_image.jpg --output path/to/output_decrypted_image.jpg --key your_encryption_key
Replace path/to/encrypted_image.jpg with the path to the encrypted image, path/to/output_decrypted_image.jpg with the desired output path for the decrypted image, and your_encryption_key with the encryption key used during encryption.


License
MIT License

Contact
For questions or support, please contact THANU2206.


