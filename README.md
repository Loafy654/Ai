# AI Doctor Assistant - Standalone Executable

A desktop application that provides AI-powered health consultation and medical guidance.

## 🚀 Quick Start

### Option 1: Use Pre-built Executable
1. Download `AI_Doctor_Assistant.exe` from the releases
2. Double-click to run
3. Enter your OpenRouter API key
4. Start consulting with your AI doctor!

### Option 2: Build from Source

#### Prerequisites
\`\`\`bash
pip install -r requirements_exe.txt
\`\`\`

#### Build Steps
1. **Clone/Download** this repository
2. **Install dependencies**:
   \`\`\`bash
   pip install -r requirements_exe.txt
   \`\`\`
3. **Run the build script**:
   \`\`\`bash
   python build_exe.py
   \`\`\`
4. **Find your executable** in the `dist/` folder

## 📁 File Structure
\`\`\`
AI_Doctor_Assistant/
├── app.py                 # Main Flask application
├── build_exe.py          # Build script for creating .exe
├── index.html            # Web interface
├── static/
│   ├── style.css         # Styling
│   └── script.js         # Frontend logic
├── requirements_exe.txt  # Python dependencies
└── README.md            # This file
\`\`\`

## 🔧 Features

- **Standalone Desktop App** - No installation required
- **AI Health Consultation** - Powered by OpenRouter API
- **Symptom Analysis** - Describe symptoms and get guidance
- **Medical Information** - Ask about medications, conditions, etc.
- **Safety First** - Always recommends professional medical care
- **Auto-opens Browser** - Launches web interface automatically
- **Portable** - Single .exe file, runs anywhere

## 🏥 Usage

1. **Start the Application** - Double-click `AI_Doctor_Assistant.exe`
2. **Enter API Key** - Get one from [openrouter.ai](https://openrouter.ai)
3. **Ask Health Questions** - Describe symptoms or ask medical questions
4. **Get AI Guidance** - Receive informative responses with safety reminders
5. **Seek Professional Care** - Always consult real doctors for serious concerns

## ⚠️ Important Disclaimers

- **Not a Medical Device** - This is for informational purposes only
- **Not a Replacement** - Always consult qualified healthcare professionals
- **Emergency Situations** - Call emergency services immediately for urgent care
- **Educational Tool** - Provides general health information and guidance

## 🛠 Technical Details

- **Framework**: Flask (Python web framework)
- **Frontend**: HTML, CSS, JavaScript
- **AI Provider**: OpenRouter API
- **Build Tool**: PyInstaller
- **Platform**: Windows (can be adapted for Mac/Linux)

## 📦 Distribution

The built executable (`AI_Doctor_Assistant.exe`) is completely self-contained and includes:
- Python runtime
- Flask web server
- All HTML, CSS, and JavaScript files
- Required Python libraries

Users don't need Python installed to run the application.

## 🔒 Privacy & Security

- **Local Processing** - Runs entirely on your computer
- **No Data Storage** - Conversations are not saved
- **API Key Security** - Your key stays on your device
- **HTTPS Communication** - Secure connection to AI services

## 🆘 Support

For issues or questions:
1. Check that you have a valid OpenRouter API key
2. Ensure internet connection for AI services
3. For emergencies, contact emergency services immediately

---

**Remember**: This AI assistant provides general health information only. Always consult healthcare professionals for medical advice, diagnosis, or treatment.
