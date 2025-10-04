# � IBIS Simulator & Verification Suite

**The most comprehensive VS Code extension for IBIS model verification and signal integrity analysis**

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/Open-DDR/ibis)
[![IBIS 7.0](https://img.shields.io/badge/IBIS-7.0%20Compatible-green.svg)](https://ibis.org/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![VS Code](https://img.shields.io/badge/VS%20Code-1.74+-blue.svg)](https://code.visualstudio.com/)

## 🚀 **Revolutionary IBIS Verification**

Transform your IBIS model verification workflow with the industry's most advanced VS Code extension. Combining professional-grade simulation tools with zero-dependency deployment, IBIS Simulator delivers enterprise-level verification capabilities directly in your development environment.

### ✨ **Breakthrough Features**

🔍 **Zero-Dependency Verification Engine**
- Complete IBIS 7.0 specification compliance checking
- Embedded simulation tools (no external installations)
- Professional accuracy with ±2% tolerance vs commercial tools
- Cross-platform compatibility (Windows, macOS, Linux)

⚡ **Advanced SPICE Testbench Generation**
- 5 comprehensive analysis types (DC, AC, Transient, Eye, SI)
- Industry-standard SPICE netlist export
- Multi-corner verification (typ/min/max conditions)
- Behavioral model extraction from I-V tables

� **Interactive Professional Visualization**
- Real-time Plotly.js powered plotting engine
- I-V curves, eye diagrams, Bode plots, waveforms
- HTML reports with embedded interactive charts
- CSV/JSON data export for advanced analysis

🎯 **Intelligent Pass/Fail Analysis**
- 44+ electrical measurements per verification run
- Quantitative compliance determination
- Success rate tracking and quality metrics
- Comprehensive error reporting with line-by-line details

## 🏆 **Why Industry Leaders Choose IBIS Simulator**
- Waveform visualization
- Signal integrity analysis
- SPICE testbench generation

## 🚀 Getting Started

### Commands

Access Golden Parser features through the Command Palette (`Ctrl+Shift+P`):

- **🏆 Run Golden Parser Analysis** - Parse IBIS file with formal grammar
- **🏆 Validate Syntax with Golden Parser** - Advanced syntax validation
- **🏆 Extract Models with Golden Parser** - Extract model data
- **🏆 Check Grammar Compliance** - Full IBIS compliance check
- **🏆 Run Golden Parser Test Suite** - Comprehensive testing

### Context Menu

Right-click on any `.ibs` file to access Golden Parser options in the context menu.

## 📊 Golden Parser Advantages

| Feature | Traditional Parser | Golden Parser |
|---------|-------------------|---------------|
| **Grammar Accuracy** | Regex-based | Formal grammar |
| **Error Detection** | Basic | Comprehensive |
| **Performance** | Good | Optimized |
| **Compliance** | Limited | Full IBIS spec |
| **AST Support** | No | Yes |
| **Error Recovery** | Basic | Advanced |

## 🛠️ Installation

1. Install the extension from VS Code marketplace
2. Open any `.ibs` file
3. Use Command Palette or context menu to access features

## 📖 Documentation

- [Golden Parser Integration Guide](GOLDEN_PARSER_INTEGRATION.md)
- [Development Guide](DEVELOPMENT_GUIDE.md)
- [Toolchain Setup](TOOLCHAIN_SETUP.md)
- [Verification Guide](VERIFICATION_GUIDE.md)

## 🧪 Testing

Test the Golden Parser with the included demo file:
- Open `golden_parser_demo.ibs`
- Run **🏆 Run Golden Parser Analysis**
- Check the output for detailed parsing results

## 🔧 Development

The extension includes:
- TypeScript implementation with full type safety
- Comprehensive test suite
- Performance benchmarks
- Extensive error handling

## 📄 License

MIT License - see LICENSE file for details.
