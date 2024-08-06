# Image Encryption Tool

This is a simple image encryption tool using pixel manipulation. The tool allows users to encrypt and decrypt images by performing basic operations on the pixel values.

Usage:

an Image..
python image_encryption.py encrypt <image_path> [--swap]

Decrypt an Image..
python image_encryption.py decrypt <image_path> [--swap]

Example of usage..

python image_encryption.py encrypt images/input_image.png 50 --swap python image_encryption.py decrypt encrypted_image.png 50 --swap
