# Image Encryption Tool 

This project is a simple image encryption and decryption tool built using Python.
It works by modifying pixel values of an image using a key.

## What this project does

- Encrypts an image by changing pixel values  
- Decrypts the image back to original  
- Uses a simple mathematical operation on RGB values  

## How it works

- Each pixel has RGB values (Red, Green, Blue)
- Encryption adds a key value to each pixel
- Decryption subtracts the same key value
- Modulo operation ensures values stay within valid range (0–255)

## How to run

1. Place your image in the same folder as the Python file  
2. Run the program  
3. It will generate:
   - encrypted.png  
   - decrypted.png  

## About

This project helped me understand:
- How images are stored as pixel data  
- How encryption can be applied to images  
- Basic concepts of data security  

## Author
Angel Xavier
