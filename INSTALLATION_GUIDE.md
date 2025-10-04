# 🎯 IBIS Simulator - Installation Guide

## 📥 **Easy Installation from Binary**

This folder contains the pre-built IBIS Simulator extension ready for immediate installation in VS Code.

---

## 🚀 **Quick Install (Recommended)**

### **Method 1: Command Line Installation**
```bash
# Install directly from the VSIX file
code --install-extension ibis-simulator-1.0.5.vsix

# Restart VS Code
code --relaunch
```

### **Method 2: VS Code Extensions Panel**
1. Open VS Code
2. Open Extensions panel (`Ctrl+Shift+X`)
3. Click the "..." menu (three dots)
4. Select "Install from VSIX..."
5. Navigate to this folder and select `ibis-simulator-1.0.5.vsix`
6. Click "Install"
7. Restart VS Code when prompted

### **Method 3: Drag & Drop (VS Code 1.74+)**
1. Open VS Code
2. Drag `ibis-simulator-1.0.5.vsix` into the VS Code window
3. Click "Install" when prompted
4. Restart VS Code

---

## ✅ **Verify Installation**

1. Open Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`)
2. Type "IBIS" - you should see:
   - 🎯 IBIS: Open Enhanced GUI
   - 📈 IBIS: Open I-V Curve Designer
   - ⚡ IBIS: Open V-T Waveform Analyzer
   - 📊 IBIS: Open Ramp Rate Calculator
   - 🎯 IBIS: Open Corner Analysis Suite

3. **Test Basic Functionality**:
   - Run "IBIS: Open Enhanced GUI"
   - You should see the main IBIS interface open in a new panel

---

## 🎯 **Quick Start**

### **1. Open the Main Interface**
```
Ctrl+Shift+P → "IBIS: Open Enhanced GUI"
```

### **2. Try Individual Tools**
- **I-V Curve Designer**: Analyze driver output characteristics
- **V-T Waveform Analyzer**: Examine timing behavior
- **Ramp Rate Calculator**: Calculate slew rates
- **Corner Analysis Suite**: Multi-corner verification

### **3. Context Menu Integration**
- Right-click any `.ibs` file
- Access IBIS analysis tools directly from context menu

---

## 🔧 **System Requirements**

- **VS Code**: Version 1.74.0 or higher
- **Operating System**: Windows, macOS, or Linux
- **Memory**: 4GB RAM minimum (8GB recommended)
- **Storage**: 50MB free space

---

## 📦 **What's Included**

This binary package contains:
- ✅ **Complete IBIS 7.0 verification engine**
- ✅ **Embedded simulation tools** (no external dependencies)
- ✅ **Professional GUI interface** with interactive charts
- ✅ **Real-time visualization** powered by Plotly.js
- ✅ **Zero-setup deployment** - everything bundled

---

## 🐛 **Troubleshooting**

### **Installation Issues**
```bash
# Check VS Code version
code --version

# Force reinstall if needed
code --uninstall-extension undefined_publisher.ibis-simulator
code --install-extension ibis-simulator-1.0.5.vsix
```

### **Extension Not Appearing**
1. Restart VS Code completely
2. Check Extensions panel for "IBIS Simulator"
3. Try reloading window (`Ctrl+Shift+P` → "Reload Window")

### **Commands Not Available**
1. Ensure extension is enabled in Extensions panel
2. Check for any error notifications
3. Open Developer Console (`Help` → `Toggle Developer Tools`)

---

## 📖 **Documentation**

- **`USER_GUIDE.md`** - Complete feature documentation
- **`BINARY_RELEASE_GUIDE.md`** - Release and deployment guide
- **GitHub Repository**: https://github.com/Open-DDR/ibis

---

## 🎖️ **Version Information**

- **Extension Version**: 1.0.5
- **IBIS Specification**: 7.0 Compatible
- **Package Size**: ~646KB
- **Build Date**: October 2025

---

## 🤝 **Support & Feedback**

- **Issues**: Report bugs at GitHub Issues
- **Features**: Request new features via GitHub Discussions
- **Questions**: Check the USER_GUIDE.md or open GitHub Discussion

**Enjoy professional-grade IBIS model verification in VS Code!** 🚀