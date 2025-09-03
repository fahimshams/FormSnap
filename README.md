# FormSnap
Cross-platform mobile app to capture forms via photo, extract fields with OCR, and provide multi-language translation. Built with React Native, TypeScript, and cloud OCR services.

# Formly OCR

Formly OCR is a cross-platform **iOS & Android** app that lets you **snap a photo of any form** and automatically detects and extracts the fields. It supports **multi-language OCR and translation**, making it ideal for global use. Users can review, edit, and export extracted form data seamlessly.

## Features

- 📸 **Photo Capture & Upload**: Use camera or gallery to capture forms.
- 🧠 **OCR Field Detection**: Detects labels and associated fields using on-device or cloud OCR.
- 🌎 **Multi-Language Support**: Recognizes and translates forms in multiple languages.
- ✍️ **Editable Fields**: Users can correct or fill in missing information.
- 💾 **Export & Save**: Export extracted data as JSON or integrate with other apps.
- 🔧 **Cross-Platform**: Works on **iOS and Android** using React Native & TypeScript.

## Tech Stack

- **Frontend**: React Native, Expo, TypeScript
- **Backend (optional)**: Node.js / Express (for cloud OCR & translation)
- **OCR**: Tesseract.js (offline) or Google Cloud Vision / Document AI (cloud)
- **Translation APIs**: Google Translate API, DeepL API

## Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/formly-ocr.git
cd formly-ocr

# Install dependencies
npm install

# Run app (Expo)
npx expo start

