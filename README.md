# SwiftPDFApp

A fast and efficient cross-platform PDF reader application built with modern web technologies and Capacitor framework for native mobile deployment.

## 🎯 Overview

SwiftPDFApp is a lightweight PDF reader designed for seamless document viewing across web and mobile platforms. Built with JavaScript and powered by Capacitor, it provides native functionality for Android and web browsers while maintaining a clean, intuitive user interface.

## ✨ Features

- **📱 Cross-Platform Support** - Run on web browsers and Android devices with a single codebase
- **📄 PDF Viewing** - Smooth and responsive PDF document rendering
- **💾 File Management** - Direct file system access and document handling via Capacitor Filesystem API
- **⚙️ Preferences** - User preferences and settings persistence using Capacitor Preferences
- **🎨 Clean UI** - Responsive HTML interface for optimal viewing experience
- **⚡ Lightweight** - Minimal dependencies for fast loading and execution

## 🏗️ Project Structure

```
SwiftPDFApp/
├── www/                          # Web application files
│   ├── index.html               # Main application interface
│   └── assets/                  # Static resources
├── android/                      # Android native code
├── resources/                    # App icons and splash screens
├── package.json                 # Project configuration
└── README.md                    # This file
```

## 🚀 Getting Started

### Prerequisites

- **Node.js** (v14 or higher)
- **npm** (v6 or higher)
- **Android Studio** (for Android deployment)
- **Java Development Kit** (JDK 11+)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/G3TECH1/SwiftPDFApp.git
   cd SwiftPDFApp
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Build assets:**
   ```bash
   npm run build
   ```

### Running the Application

#### Web Browser
```bash
# Navigate to the www directory and serve with a local server
cd www
npx http-server
```

#### Android Device
```bash
# Sync files to Android platform
npx cap sync

# Open in Android Studio
npx cap open android

# Build and run from Android Studio
```

## 📦 Dependencies

### Runtime Dependencies
- `@capacitor/core@^8.4.1` - Core Capacitor framework
- `@capacitor/android@^8.4.1` - Android platform support
- `@capacitor/cli@^8.4.1` - CLI tools for Capacitor
- `@capacitor/filesystem@^8.1.2` - File system access
- `@capacitor/preferences@^8.0.1` - Persistent preferences storage

### Development Dependencies
- `@capacitor/assets@^3.0.5` - Asset generation and management

## 🔧 Configuration

### package.json
The project uses npm for dependency management. Key configurations:
- **Name:** swiftpdfapp
- **Version:** 1.0.0
- **License:** ISC
- **Entry Point:** index.js

## 💡 Usage

### Basic PDF Viewing
1. Launch the application
2. Select or upload a PDF file
3. Use the interface to navigate through pages
4. Zoom and pan for better readability

### File Operations
The app utilizes Capacitor's Filesystem API to:
- Read PDF files from device storage
- Access user documents
- Manage file permissions on Android

### Saving Preferences
User settings and preferences are automatically saved and restored using Capacitor Preferences API.

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

## 📋 Development Guidelines

- Follow JavaScript ES6+ standards
- Keep code modular and reusable
- Test on both web and Android platforms
- Ensure responsive design for various screen sizes
- Document new features and API changes

## 🐛 Issue Reporting

Found a bug? Please create an issue with:
- Clear description of the problem
- Steps to reproduce
- Expected vs actual behavior
- Screenshots or error messages
- Device/browser information

## 📄 License

This project is licensed under the ISC License - see the LICENSE file for details.

## 📞 Support

For questions, suggestions, or support:
- Open an issue on GitHub
- Check existing issues for similar problems
- Review the documentation in the wiki

## 🎓 Learn More

- [Capacitor Documentation](https://capacitorjs.com/)
- [Capacitor Filesystem API](https://capacitorjs.com/docs/apis/filesystem)
- [Capacitor Preferences API](https://capacitorjs.com/docs/apis/preferences)
- [Android Development Guide](https://developer.android.com/)

## 📈 Roadmap

Future features and improvements planned for SwiftPDFApp:
- [ ] Advanced PDF annotation tools
- [ ] Text search functionality
- [ ] Bookmark management
- [ ] Dark mode support
- [ ] PDF form filling
- [ ] iOS platform support
- [ ] Cloud storage integration

---

**Made with ❤️ by G3TECH1**

Last updated: 2026
