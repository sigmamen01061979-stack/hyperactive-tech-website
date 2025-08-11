# HyperActive Tech - Intelligent Automation Software

![HyperActive Tech Logo](https://via.placeholder.com/800x200/6667ea/ffffff?text=HyperActive+Tech)

**Control your devices through natural language commands and AI-powered automation**

HyperActive Tech is an intelligent automation software that allows you to control your computer, smartphone, and other devices using natural language commands. Simply speak or type what you want to do, and the software will analyze your screen and execute the tasks automatically.

## 🚀 Features

- **Natural Language Processing**: Understand commands in plain English
- **Voice Control**: Use voice commands for hands-free operation  
- **Cross-Platform Support**: Works on macOS, Windows, Android, and iOS
- **Screen Analysis**: AI-powered screen understanding and element detection
- **Privacy First**: All processing happens locally on your device
- **Smart Automation**: Learn from your patterns and preferences
- **Real-time Execution**: Execute complex tasks in milliseconds

## 🎯 Use Cases

- **Productivity Automation**: "Open my email and reply to John's message"
- **Web Navigation**: "Search for Python tutorials on Google"
- **File Management**: "Create a new folder called 'Project Files'"
- **Application Control**: "Take a screenshot and save it to Desktop"
- **Text Processing**: "Type 'Hello World' and press Enter"
- **And much more!**

## 📋 Requirements

- **Operating System**: macOS 11+, Windows 10+, Android 8+, or iOS 14+
- **Python**: 3.8 or higher (for desktop versions)
- **RAM**: Minimum 4GB (8GB recommended)
- **Storage**: 500MB free space
- **Internet**: Optional (for enhanced voice recognition)

## 🔧 Installation

### Desktop (macOS/Windows/Linux)

1. **Clone or Download** the repository:
   ```bash
   git clone https://github.com/hyperactivetech/hyperactive-tech.git
   cd hyperactive-tech
   ```

2. **Run Setup**:
   ```bash
   python setup.py
   ```

3. **Start the Application**:
   ```bash
   python hyperactive_tech_launcher.py
   ```

### Quick Install Script

```bash
# Download and run the installer
curl -sSL https://install.hyperactivetech.com | python3
```

### Mobile (Android/iOS)

Download the app from:
- **Android**: [Google Play Store](https://play.google.com/store/apps/details?id=com.hyperactivetech.automation)
- **iOS**: [App Store](https://apps.apple.com/app/hyperactive-tech/id123456789)

## 🛡️ Permissions & Privacy

HyperActive Tech requires certain permissions to function:

### Required Permissions

| Permission | Purpose | Platform |
|------------|---------|----------|
| **Screen Recording** | Analyze screen content for automation | All |
| **Accessibility** | Control keyboard and mouse input | All |
| **Input Control** | Execute automation commands | All |

### Optional Permissions

| Permission | Purpose | Platform |
|------------|---------|----------|
| **Microphone** | Voice command input | All |
| **Camera** | Advanced screen analysis | Mobile |

### Privacy Guarantee

✅ **All data processing happens locally on your device**  
✅ **No personal data is transmitted to external servers**  
✅ **You can revoke permissions at any time**  
✅ **Open source code available for security audits**

## 🎮 Usage

### GUI Mode (Recommended)

1. Launch the application using the GUI
2. Click "Start" to begin automation services
3. Type commands in the input field or use voice commands
4. Watch as your commands are executed automatically

### Console Mode

```bash
python hyperactive_tech_launcher.py --headless
```

### Voice Commands

Say the wake word **"HyperActive"** followed by your command:

- *"HyperActive, click on the submit button"*
- *"HyperActive, type hello world"*
- *"HyperActive, take a screenshot"*
- *"HyperActive, scroll down"*

### Text Commands

Type commands directly:

- `click on login button`
- `type "username@example.com"`
- `scroll down 3 times`
- `wait 2 seconds`
- `take screenshot`

## 📖 Command Examples

### Basic Actions
```
click on button
click on "Submit"
double click on file
right click on image
```

### Text Input
```
type "Hello World"
type username
enter password "mypassword"
```

### Navigation
```
scroll down
scroll up 5 times
scroll left
page down
```

### System Control
```
take screenshot
wait 3 seconds
press enter
press ctrl+c
```

### Complex Tasks
```
open email and reply to latest message
search for "automation tools" and click first result
find the download button and click it
```

## 🔧 Configuration

The application creates a configuration directory at:
- **macOS/Linux**: `~/.hyperactivetech/`
- **Windows**: `%USERPROFILE%\.hyperactivetech\`

### Main Config File: `config.yaml`

```yaml
app:
  name: 'HyperActive Tech'
  auto_start: false
  minimize_to_tray: true

automation:
  screenshot_interval: 0.5
  command_timeout: 30.0
  confidence_threshold: 0.7

ai:
  model: 'local'
  voice_language: 'en-US'
  enable_voice: true
  voice_activation_phrase: 'hyperactive'

privacy:
  store_commands: false
  encrypt_logs: true
  auto_delete_logs_days: 30
```

## 🚨 Troubleshooting

### Common Issues

**"Permission Denied" Error**
- Grant required permissions in system settings
- On macOS: System Preferences → Security & Privacy
- On Windows: Windows Settings → Privacy & Security

**"Command Not Recognized"**
- Try rephrasing your command more simply
- Check if automation services are running
- Verify screen content is visible and clear

**"Voice Commands Not Working"**
- Check microphone permissions
- Ensure microphone is not muted
- Try using text commands instead
- Check if wake word detection is enabled

**"Screen Capture Failed"**
- Grant screen recording permissions
- Close other screen recording applications
- Restart the application

### Platform-Specific Issues

#### macOS
- Enable "Screen Recording" in System Preferences
- Enable "Accessibility" permissions
- Disable "Reduce Motion" for better performance

#### Windows
- Run as Administrator if needed
- Disable Windows Defender real-time protection temporarily
- Check Windows Display Scale settings

#### Android/iOS
- Enable Accessibility Services
- Allow "Display over other apps"
- Grant microphone permissions for voice

## 🛠️ Development

### For Developers

1. **Clone the repository**:
   ```bash
   git clone https://github.com/hyperactivetech/hyperactive-tech.git
   cd hyperactive-tech
   ```

2. **Install development dependencies**:
   ```bash
   pip install -r requirements.txt
   pip install pytest black flake8
   ```

3. **Run tests**:
   ```bash
   pytest tests/
   ```

4. **Code formatting**:
   ```bash
   black hyperactive_tech/
   flake8 hyperactive_tech/
   ```

### Project Structure

```
hyperactive_tech/
├── core/               # Core application logic
├── automation/         # Automation engines
├── ai/                # AI and NLP components  
├── ui/                # User interface
├── utils/             # Utility functions
├── main.py            # Application entry point
└── __init__.py
```

## 📱 Mobile Apps

### Android
- **Package**: `com.hyperactivetech.automation`
- **Min SDK**: API 26 (Android 8.0)
- **Permissions**: Accessibility Services, Screen Capture, Microphone

### iOS
- **Bundle ID**: `com.hyperactivetech.automation`
- **Min Version**: iOS 14.0
- **Permissions**: Limited by iOS sandbox restrictions

## 🌐 Website Integration

Visit **www.hyperactivetech.com** to:
- Download the latest version
- Access documentation
- Join the community
- Report issues
- Get support

The website includes:
- Modern responsive design
- Download links for all platforms
- Feature demonstrations
- Privacy information
- Support resources

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

We welcome contributions! Please read our [Contributing Guidelines](CONTRIBUTING.md) first.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

- **Website**: https://www.hyperactivetech.com
- **Email**: support@hyperactivetech.com
- **Discord**: [Join our community](https://discord.gg/hyperactivetech)
- **Documentation**: [docs.hyperactivetech.com](https://docs.hyperactivetech.com)
- **Issues**: [GitHub Issues](https://github.com/hyperactivetech/issues)

## 🙏 Acknowledgments

- OpenCV community for computer vision tools
- SpeechRecognition library contributors  
- PyAutoGUI and pynput developers
- All beta testers and contributors

---

**Made with ❤️ by the HyperActive Tech Team**

*Empowering everyone with intelligent automation*
