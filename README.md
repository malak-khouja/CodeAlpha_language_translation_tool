# Language Translation Tool - CodeAlpha Internship Project

A React-based web application that allows users to translate text between languages using an external translation API. It features dropdowns to choose source and target languages, and displays the translated text dynamically.

## 🌐 Features

- Select source and target languages from dropdown menus
- Enter text to be translated
- Live translation using API (LibreTranslate and local model)
- Display translated text
- Error handling and clean UI with Bootstrap

## 🛠️ Technologies Used

- React.js
- Bootstrap (React-Bootstrap)
- LibreTranslate API and local model endpoint
- JavaScript (Fetch API)

## 🔧 How It Works

1. Fetches available languages from `https://libretranslate.com/languages`
2. User enters text and selects languages
3. The text is sent to a local translation endpoint 
4. The translated text is parsed from the response stream and displayed

## 📦 Installation & Usage

1. Clone the repository:
```bash
git clone https://github.com/malak-khouja/language-translation-tool.git
cd language-translation-tool
