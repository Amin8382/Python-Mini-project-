# Image Steganography Tool

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.10-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Tkinter-GUI-FF6F00?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Pillow-10.0-008080?style=for-the-badge&logo=python&logoColor=white" />
</div>

## Overview

Desktop GUI application for hiding and extracting secret messages in images using LSB (Least Significant Bit) steganography. Supports PNG and JPEG image formats with an intuitive Tkinter interface.

## Features

- **Message Hiding**: Embed secret text messages into images using LSB technique
- **Message Extraction**: Retrieve hidden messages from steganographic images
- **Format Support**: Compatible with PNG and JPEG image formats
- **User-Friendly GUI**: Clean Tkinter-based desktop interface

## How LSB Steganography Works

Least Significant Bit steganography works by replacing the least significant bit of each pixel's color channel with a bit from the secret message. The change is imperceptible to the human eye but can store a significant amount of data.

## Tech Stack

| Component | Technology |
|-----------|-----------|
| **Language** | Python 3.10 |
| **GUI Framework** | Tkinter |
| **Image Processing** | Pillow (PIL) |

## Getting Started

```bash
git clone https://github.com/Amin8382/Python-Mini-project-.git
cd Python-Mini-project-
python main.py
```
