# Image Encryption Tool

This is a simple image encryption tool that uses pixel manipulation to encrypt and decrypt images. It supports basic mathematical operations and pixel swapping for encryption.

### Usage

# Encrypt an Image

python image_encryption.py encrypt <image_path> <key> [--swap]

# Decrypt an Image

python image_encryption.py decrypt <image_path> <key> [--swap]


# Example of usage..

python image_encryption.py encrypt images/input_image.png 50 --swap
python image_encryption.py decrypt encrypted_image.png 50 --swap
