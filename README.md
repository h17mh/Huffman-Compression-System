# Huffman Compression System

A lossless file compression and decompression system implemented in C++ using Huffman Coding. The project compresses BMP image files by assigning variable-length binary codes based on character frequencies, reducing storage requirements while preserving the original data.

## Features

* Character frequency analysis
* Huffman Tree construction
* Recursive Huffman code generation
* Bit-level file compression
* File decompression and reconstruction
* Export of generated Huffman codes
* Support for BMP image files
* Lossless data recovery

## Technologies Used

* C++
* Data Structures
* Algorithms
* File Handling
* Bit Manipulation
* Binary I/O

## Data Structures Implemented

* Custom Linked Lists
* Binary Huffman Tree
* Code Mapping Structure

## How It Works

1. Read the input BMP file.
2. Compute character frequencies.
3. Build the Huffman Tree.
4. Generate Huffman codes recursively.
5. Compress the file using binary encoding.
6. Save generated codes to `code.txt`.
7. Decompress the compressed file and reconstruct the original image.

## Project Structure

```text
src/
└── main.cpp

examples/
├── f1(before compression).bmp
├── f2 (compressed).bmp
├── f4 (decompressed).bmp
└── code.txt
```

## Performance

The system was tested on BMP image files.

| Metric               | Value  |
| -------------------- | ------ |
| Original File Size   | 100 KB |
| Compressed File Size | 58 KB  |
| Space Reduction      | 42%    |

The decompressed image matched the original image exactly, demonstrating lossless compression.

## File Support

The compression algorithm operates on binary data and can be applied to any file type. The project was tested using BMP image files as an example.

## Algorithms Used

* Huffman Coding
* Binary Tree Traversal
* Recursive Code Generation
* Bitwise Encoding and Decoding

## Future Improvements

* Graphical User Interface (GUI)
* Improved compression efficiency


## Author

Hazem Bakr
