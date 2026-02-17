# 📄 Document Validator

A web-based application for scanning DOCX documents and validating Ukrainian city/town names against customizable white and black lists.

Веб-додаток для сканування документів DOCX та перевірки українських назв міст/населених пунктів за допомогою налаштовуваних білого та чорного списків.

## 🌐 Live Demo

**[https://documentvalidator.github.io](https://documentvalidator.github.io)**

## ✨ Features

### Document Processing
- 📤 Drag & drop or click to upload DOCX files
- 📝 Automatic text extraction from documents
- 🔍 Smart scanning for Ukrainian city names
- 🎯 Highlights found cities in document preview

### White & Black Lists
- ✅ **Whitelist** - Approved/allowed cities
- 🚫 **Blacklist** - Forbidden/flagged cities
- ➕ Add custom cities to either list
- 🏷️ Preset tags for popular Ukrainian cities
- 🏷️ Preset tags for occupied territories

### Results & Statistics
- 📊 Visual summary with statistics cards
- 📋 Detailed results table
- 🏷️ Status badges for each found city
- ⚡ Quick actions to categorize unknown cities

### User Experience
- 🇺🇦 Ukrainian language (default)
- 🇬🇧 English language support
- 💾 Automatic state persistence (localStorage)
- 🔄 Full state restoration on page reload
- 📱 Responsive design (mobile & desktop)
- 🔄 Portrait & landscape orientation support
- 🌙 Dark mode support
- 🔔 Toast notifications

## 🚀 Getting Started

### Option 1: Use Online
Simply visit **[https://documentvalidator.github.io](https://documentvalidator.github.io)**

### Option 2: Run Locally

1. Clone the repository:
```bash
git clone https://github.com/documentvalidator/documentvalidator.github.io.git
```

2. Navigate to the directory:
```bash
cd documentvalidator.github.io
```

3. Open `index.html` in your web browser or serve with any static file server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve

# Using PHP
php -S localhost:8000
```

4. Open `http://localhost:8000` in your browser

## 📖 Usage Guide

### 1. Upload Document
- Drag and drop a `.docx` file onto the upload zone
- Or click the upload zone to select a file

### 2. Configure Lists
**Whitelist (Білий список):**
- Add cities that are approved/allowed
- Use preset tags for quick addition of popular Ukrainian cities

**Blacklist (Чорний список):**
- Add cities that should be flagged/forbidden
- Use preset tags for occupied territories

### 3. Scan Document
- Click "🔍 Scan Document" button
- Wait for the scanning process to complete
- Review the results

### 4. Review Results
- Check the summary statistics
- Review the detailed table
- Add unknown cities to appropriate lists using quick action buttons

### 5. Document Preview
- View the extracted text with highlighted cities
- Green highlights = whitelist cities
- Red highlights = blacklist cities

## 🗂️ Project Structure

```
documentvalidator.github.io/
│
├── index.html      # Main application (HTML + CSS + JavaScript)
├── README.md       # Documentation
└── LICENSE         # MIT License
```

## 🔧 Technical Details

### Dependencies
- **[Mammoth.js](https://github.com/mwilliamson/mammoth.js)** - DOCX to text conversion (loaded via CDN)
- **[Google Fonts](https://fonts.google.com/)** - Roboto & Montserrat fonts

### Data Storage
All application data is stored in browser's `localStorage`:
- Whitelist cities
- Blacklist cities
- Document text
- Scan results
- Language preference

### Built-in Ukrainian Cities Database
The application includes a comprehensive database of Ukrainian cities:
- Regional centers (обласні центри)
- Major cities (великі міста)
- Crimean cities (міста Криму)
- Other significant settlements

## 🌍 Localization

The application supports two languages:
- 🇺🇦 **Ukrainian** (default)
- 🇬🇧 **English**

Switch languages using the language toggle in the header.

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Ideas for Contribution
- Add more Ukrainian cities to the database
- Add support for additional file formats
- Improve city detection algorithm
- Add export functionality for results
- Add more language translations

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 👏 Acknowledgments

- Ukrainian city names database compiled from official sources
- Icons and emojis from Unicode standard
- Mammoth.js team for the excellent DOCX parsing library

## 📧 Contact

- **Repository:** [https://github.com/documentvalidator/documentvalidator.github.io](https://github.com/documentvalidator/documentvalidator.github.io)
- **Issues:** [https://github.com/documentvalidator/documentvalidator.github.io/issues](https://github.com/documentvalidator/documentvalidator.github.io/issues)

---

<p align="center">
  Made with ❤️ for Ukraine 🇺🇦
</p>
