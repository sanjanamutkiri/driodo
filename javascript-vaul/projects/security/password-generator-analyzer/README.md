# Password Generator & Strength Analyzer

## 🚀 Overview
A comprehensive password security tool that generates cryptographically secure passwords and analyzes password strength in real-time. Built with vanilla JavaScript, this tool provides advanced security features including entropy calculation, pattern detection, and detailed security feedback.

## 🔧 Features
- **Smart Password Generation**: Generates secure passwords with customizable length (4-128 characters)
- **Character Type Selection**: Choose from uppercase, lowercase, numbers, and special characters
- **Real-time Strength Analysis**: Advanced algorithm that evaluates password security
- **Entropy Calculation**: Measures password randomness using information theory
- **Pattern Detection**: Identifies common weak patterns and dictionary words
- **Visual Feedback**: Color-coded strength meter and detailed security recommendations
- **One-Click Copy**: Easy clipboard integration for generated passwords
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **No Dependencies**: Pure vanilla JavaScript with no external libraries

## 🛠️ Tech Stack
- **JavaScript (ES6+)**: Core functionality and password algorithms
- **HTML5**: Semantic markup and modern input types
- **CSS3**: Advanced styling with gradients, animations, and responsive design
- **Web Crypto API**: Secure random number generation
- **Clipboard API**: Modern copy-to-clipboard functionality

## 📦 How to Run
1. Clone or download the project files
2. Open `index.html` in any modern web browser
3. No installation or build process required!

```bash
# If using a local server (optional)
python -m http.server 8000
# or
npx serve .
```

## 🔐 Security Features
- **Entropy Analysis**: Calculates password randomness using Shannon entropy
- **Pattern Recognition**: Detects common weak patterns like "123", "abc", "qwe"
- **Dictionary Detection**: Identifies common words like "password", "admin"
- **Repetition Analysis**: Flags excessive character repetition
- **Character Variety**: Ensures diverse character set usage
- **Length Validation**: Recommends optimal password lengths

## 📊 Password Strength Scoring
- **Weak (0-2 points)**: Basic passwords with limited character variety
- **Medium (3-4 points)**: Decent passwords with some complexity
- **Strong (5-6 points)**: Good passwords with high complexity
- **Very Strong (7-8 points)**: Excellent passwords with maximum security

## 🎯 Use Cases
- **Personal Security**: Generate strong passwords for personal accounts
- **Development**: Integrate password validation into web applications
- **Education**: Learn about password security best practices
- **Security Auditing**: Analyze existing passwords for vulnerabilities
- **Corporate Training**: Teach employees about password security

## 🔬 Advanced Features
- **Cryptographic Randomness**: Uses `crypto.getRandomValues()` for secure generation
- **Adaptive UI**: Dynamic feedback based on password complexity
- **Accessibility**: Proper ARIA labels and keyboard navigation
- **Performance**: Optimized algorithms for real-time analysis
- **Cross-browser**: Compatible with all modern browsers



## 🤝 Contributing
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit changes: `git commit -m 'Add amazing feature'`
4. Push to branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 🛡️ Security Considerations
- Passwords are generated client-side only
- No data is sent to external servers
- Uses cryptographically secure random number generation
- Memory is cleared after password generation
- No password storage or logging

## 📝 Browser Support
- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+
