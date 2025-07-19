# Steganography Demo: Hiding Messages in Images

## Overview
This project demonstrates how steganography can be used to hide messages inside images using a web-based encoder/decoder.

## Steps
1. Chose an image: `original_flower.png`
2. Encoded a message: "Hi there, I hope you have a blessed day ahead!"
3. Downloaded the resulting image: `message_flower.png`
4. Successfully decoded the message from the image.

## Tools Used
- [Steganography Online Tool](https://stylesuxx.github.io/steganography/)
- macOS image preview for file size comparison

## File Analysis
| Image              | Size (MB) | Hidden? |
|-------------------|-----------|---------|
| original_flower.png | 29.7     | ❌ No     |
| message_flower.png  | 25.3     | ✅ Yes    |

## Message Retrieved
Hi there, I hope you have a blessed day ahead!



## Screenshots
See `/docs/` folder.

## Learnings
- How data can be encoded without noticeable image distortion.
- Stego techniques in open-source tools.
- Limitations based on image size and content.
