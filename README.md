# Mistral OCR - Arabic Web App

A modern, progressive web application for Optical Character Recognition (OCR) powered by advanced Large Language Models (LLMs) from **Mistral AI** and **Verdent AI**. Built by **Verdent** to showcase cutting-edge LLM capabilities for document scanning and text extraction.

## 🌟 Features

- **OCR Processing**: Extract text from images with high accuracy
- **Multi-Format Support**: Handle images, PDFs, and documents
- **Arabic Language Support**: Specialized support for Arabic OCR and text processing
- **Progressive Web App**: Installable on desktop and mobile devices
- **Offline-First**: Service Worker enabled for offline functionality
- **Real-Time Markdown Rendering**: Convert extracted text to formatted markdown
- **Cloud-Powered Processing**: Integration with Mistral AI and Verdent AI LLMs
- **Responsive Design**: Modern, accessible UI with dark/light theme support
- **Fast Caching**: Optimized asset caching for improved performance

## 🚀 Tech Stack

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables
- **JavaScript (Vanilla)** - No framework dependencies
- **Service Worker (SW.js)** - Offline caching and PWA functionality

### LLM Integration
- **Mistral AI** - Primary LLM for OCR and text processing
- **Verdent AI** - Advanced LLM for testing new features and capabilities

### Libraries
- **Marked.js** - Markdown parsing and rendering
- **PDF.js** - PDF document handling and extraction
- **Font Awesome** - Icon library for UI components
- **Google Fonts (Inter)** - Typography

## 📋 Project Structure

```
Mistral-ocr-arabic-web-app/
├── index.html          # Main HTML file with embedded styles and scripts
├── manifest.json       # PWA manifest configuration
├── sw.js              # Service Worker for offline caching
├── icon.svg           # Application icon (SVG)
├── icon-192.png       # App icon (192x192)
├── icon-512.png       # App icon (512x512)
└── README.md          # This file
```

## 🧪 LLM Features Under Testing

### Mistral AI Integration
- **Text Extraction**: High-accuracy OCR using Mistral's vision capabilities
- **Language Understanding**: Natural language processing for extracted text
- **Content Classification**: Automatic categorization of document types
- **Multi-language Support**: Particularly optimized for Arabic content

### Verdent AI Integration
- **Advanced Text Processing**: Novel LLM features for enhanced text understanding
- **Semantic Analysis**: Deep understanding of document context and meaning
- **Quality Assurance**: Testing new LLM architectures and capabilities
- **Core Architecture**: Verdent's proprietary LLM framework powers the platform

## 🔧 Installation & Setup

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Node.js (optional, for local development server)
- Internet connection for LLM API calls

### Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ahmed3atef/Mistral-OCR.git
   cd Mistral-ocr-arabic-web-app
   ```

2. **Local Development Server** (Optional)
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Or using Node.js/http-server
   npx http-server
   ```

3. **Access the Application**
   - Open `index.html` in your browser or
   - Navigate to `http://localhost:8000` if using a development server

4. **Configure API Keys**
   - Add your Mistral AI API key
   - Add your Verdent AI API key
   - (Configuration details in the main application)

## 📱 PWA Installation

### Desktop
1. Open the app in a modern browser
2. Click the install prompt or use the browser's "Install app" option
3. App will be installed to your desktop/applications

### Mobile
1. Open in mobile browser (iOS Safari, Android Chrome)
2. Tap "Add to Home Screen" or "Install"
3. Access the app directly from your home screen

## 🎯 Usage

1. **Upload Document**
   - Click the upload area or drag-and-drop
   - Supported: Images (JPG, PNG), PDFs

2. **Process OCR**
   - Select processing model (Mistral AI or Verdent AI)
   - Click "Extract Text" button
   - Wait for processing to complete

3. **View Results**
   - Extracted text displays in the editor
   - View rendered markdown output
   - Copy or download results as needed

4. **Arabic Support**
   - Automatic RTL detection for Arabic text
   - Proper text formatting and preservation

## 🏗️ Architecture

### Client-Side Processing
- Service Worker handles offline functionality and caching
- Vanilla JavaScript manages DOM and user interactions
- Marked.js renders markdown output

### Server-Side Integration
- API calls to Mistral AI endpoints
- API calls to Verdent AI endpoints
- Authentication via API keys

### Caching Strategy
- Static assets cached in Service Worker
- CDN resources (Google Fonts, Font Awesome) cached
- PDF.js worker cached for offline functionality

## 🔐 Security

- API keys should be stored securely (not in client-side code)
- HTTPS recommended for production
- Service Worker provides defense in depth
- No sensitive data stored in browser cache

## 📈 Performance

- **Lighthouse Optimized**: PWA, Performance, Accessibility
- **Fast Loading**: Optimized asset caching
- **Minimal Dependencies**: Vanilla JS reduces bundle size
- **Lazy Loading**: Resources loaded on-demand

## 🐛 Browser Support

| Browser | Status | Version |
|---------|--------|---------|
| Chrome  | ✅ Full Support | 90+ |
| Firefox | ✅ Full Support | 88+ |
| Safari  | ✅ Full Support | 14+ |
| Edge    | ✅ Full Support | 90+ |

## 📝 Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📚 API Documentation

### Mistral AI
- [Mistral AI Documentation](https://docs.mistral.ai)
- Vision Capabilities for OCR
- Text Processing APIs

### Verdent AI
- [Verdent AI Documentation](https://verdent.ai)
- Advanced LLM Features
- Testing Framework

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👤 Built By

**Verdent** - Building advanced LLM-powered OCR solutions

## 🙏 Acknowledgments

- Mistral AI for powerful LLM capabilities
- Verdent AI for advanced feature testing
- PDF.js for robust PDF handling
- Marked.js for markdown excellence
- Font Awesome for beautiful icons

## 📞 Contact & Support

For issues, questions, or suggestions:
- GitHub Issues: [Mistral-OCR Issues](https://github.com/Ahmed3atef/Mistral-OCR/issues)
- Website: [verdent.ai](https://verdent.ai)

## 🔄 Recent Updates

### v2.0 (Current)
- Integrated Mistral AI LLM features
- Added Verdent AI testing capabilities
- Enhanced Arabic language support
- Improved caching strategy (Cache v2)
- Optimized performance

### v1.0
- Initial PWA setup
- Basic OCR functionality
- Service Worker implementation

---

**Last Updated**: March 2026  
**Repository**: [Ahmed3atef/Mistral-OCR](https://github.com/Ahmed3atef/Mistral-OCR)
