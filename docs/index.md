<!-- Banner -->
<h1 align="center">
  Steganography Demo  
</h1>
<p align="center">
  <strong>Hiding Secret Messages Inside Innocent Images</strong><br>
  <em>A simple web-based tool demo powered by GitHub Pages</em>
</p>

<p align="center">
  <img src="../img/Message_Flower.png" alt="Demo Image" width="500"/>
</p>

---

## Overview

This project demonstrates **steganography**, the technique of hiding messages inside images without altering the visible appearance.  
Messages are converted to binary and embedded in image pixels using a browser-based encoder/decoder.

---

## Quick Demo

1. Upload a base image: `original_flower.png`
2. Enter your secret message (e.g., _"Hi there, I hope you have a blessed day ahead!"_)
3. Encode → download `message_flower.png`
4. Upload encoded image to decode the message

No backend — everything stays on your browser!

---

## Project Structure

```bash
steganography_demo/
├── img/              # Sample input/output images
├── docs/             # GitHub Pages site (this file lives here)
├── README.md         # Project description
├── analysis.md       # Analysis of this project
