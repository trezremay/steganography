# steganography
Steganography script for encoding and decoding messages into an image

### using steganography tool
So for using the steganography tool, you need to pull down the branch, and install the pillow fork, this is through the command line and instructions can be found here https://pillow.readthedocs.io/en/stable/installation.html 

### how it works
the general crux of how this works is by adding a secret message entered by the user using option 1 and can then be decoded by using option 2 once running

how the actual software works is by adding the indivual characters within the pixels so you are unable to see any alterations on the actual pictures. Then on the decode section once you upload the previously encoded image, it reads the encoded characters from the pxels and outputs the message as plain text

