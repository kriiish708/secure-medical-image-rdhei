# Secure Reversible Data Hiding in Encrypted Medical Images Using Huffman Tree Coding

## Overview

This project implements a secure Reversible Data Hiding in Encrypted Medical Images (RDHEMI) framework based on Hybrid Tree Coding (HTC) and Count Encryption.

The implementation follows the research paper:

**Reversible Data Hiding in Encrypted Medical Images Based on Huffman Tree Coding and Count Encryption**

## Features

- MED Predictor
- Prediction Error Map
- Huffman Coding (HC)
- Leaf-to-Leaf Coding (LLC)
- Hybrid Tree Coding
- Count Encryption
- Reserved Room Generation
- Bit Replacement
- Payload Extraction
- Exact Image Recovery

## Experimental Results

| Metric | Value |
|---------|------:|
| Embedding Capacity | 1,377,394 bits |
| Embedding Rate | 5.2543 bpp |
| PSNR (Original vs Encrypted) | 6.5446 dB |
| PSNR (Original vs Marked Encrypted) | 6.5462 dB |
| Entropy | 7.9994 |
| Payload Recovery | 100% |
| Image Recovery | 100% |

## Technologies Used

- Python
- NumPy
- OpenCV
- Matplotlib
- Medical Image Processing
- Huffman Coding
- Cryptography

## Reference

This implementation is based on the published research paper:

**Reversible Data Hiding in Encrypted Medical Images Based on Huffman Tree Coding and Count Encryption**
