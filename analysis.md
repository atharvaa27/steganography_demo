# 🕵️ Steganography in Images — Analysis & Walkthrough

## 🎯 Objective
To hide and retrieve secret messages inside images using browser-based steganography. This project demonstrates how image-based steganography works and analyzes the effects on image size, integrity, and message retrieval.

---

## 🛠️ Tools & Environment
- **Platform**: Web browser (HTML/JS frontend)
- **Tool Used**: [https://stylesuxx.github.io/steganography/](https://stylesuxx.github.io/steganography/)
- **Image Format**: PNG
- **Test Images**: High-resolution flower photo (Original & Encoded)

---

## 📂 Project Files
- `Original_Flower.png`: Clean source image
- `Message_Flower.png`: Same image with hidden message embedded
- `message.txt`: Text content to be hidden
- `README.md`: Project overview
- `analysis.md`: This document (detailed explanation)
- `screenshots/`: Visuals of before and after encoding/decoding

---

## 🧪 Experiment Steps

### 1. **Original Image Selection**
- Chose a clean high-resolution PNG image of a flower
- Verified dimensions and file size (~29.7MB)

### 2. **Message Preparation**
- Message embedded: `"Hi there, I hope you have blessed day ahead!"`

### 3. **Encoding Process**
- Used the Encode tab
- Uploaded image, entered message, clicked Encode
- Resulted in: `Message_Flower.png` (~25.3MB)
- Image looks visually identical to original

### 4. **Decoding Process**
- Uploaded both `Original_Flower.png` and `Message_Flower.png`
- Decoding from encoded image was successful — original message retrieved exactly

---

## 🧠 Observations

| Aspect             | Observation |
|--------------------|-------------|
| **Visual Quality** | No visible difference between original and encoded |
| **File Size**      | ~4.4MB reduction after encoding (possibly due to compression) |
| **Message Retrieval** | Successful using tool’s decode function |
| **Security Risk**  | Can bypass superficial content inspection tools |

---

## 🔍 Security Implications

- **Steganography** can be used for:
  - Secure communication
  - CTF challenges
  - Malware payload delivery (by attackers)
- **Defenders** must use **steganalysis tools** to scan images in sensitive environments.

---

## 📸 Screenshots

- Encoding UI: `/screenshots/encode.png`
- Encoded vs Original (file info): `/screenshots/comparison.png`
- Decoding test: `/screenshots/decoded.png`

---

## 📘 Learnings

- Basic principles of LSB (Least Significant Bit) steganography
- How image metadata and size can subtly change
- Importance of analyzing “invisible” content in cybersecurity

---

## 🏁 Conclusion

This was a fun and insightful experiment demonstrating the real-world use of steganography. The results reinforced the importance of understanding how benign-looking files can carry sensitive or malicious information.

