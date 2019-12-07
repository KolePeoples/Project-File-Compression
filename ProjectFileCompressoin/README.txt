Project File Compression
========================

The code in this project was adapted from the github below:
https://github.com/m2omou/huffman-encoding


This java program is designed to compress files using Huffman encoding.

Implementation of variants of Huffman encoding, a lossless data compression algorithm that is used in encoding schemes such as JPEG and MP3 (MPEG-1).

###Encode###

Takes in a file name, compresses the file, and outputs the compressed file with a codemap header.

Usage:
======
```java
java Schubs [target] [destination]
```

- Target: The name of the file, folder to be compressed
- Destination: The name of the output file

###Decode###

Decoding reverse the `encode` operation. Given any valid output file from encode, decode
should reproduce the original file.

####Usage:####
```java
java Deschubs [target] [destination]
```

- Target: The name of the file, folder to be decompressed
- Destination: The name of the decompressed file (to be created)

 

 
