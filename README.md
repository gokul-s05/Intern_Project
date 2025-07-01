# Cybersecurity Tools Suite

A collection of Python-based cybersecurity and encryption tools with graphical user interfaces. This project includes various tools for encryption, password management, and system monitoring.

## Tools Included

### 1. Caesar Cipher
A classical encryption tool with a modern GUI that allows users to:
- Encrypt and decrypt text using the Caesar cipher algorithm
- Specify custom shift values
- View real-time results
- User-friendly interface with clear input/output sections

### 2. Password Strength Checker
A comprehensive password analysis tool that:
- Evaluates password strength based on multiple criteria
- Provides detailed password composition analysis
- Features a strength meter with visual feedback
- Generates secure random passwords
- Includes copy-to-clipboard functionality
- Shows specific counts of character types (lowercase, uppercase, numbers, etc.)

### 3. Keylogger
A keyboard monitoring tool with GUI that offers:
- Start/stop logging functionality
- Real-time key capture display
- Log file saving capabilities
- Clear logs option
- Status indicators for logging state

### 4. Image Encryption/Decryption
An image security tool that provides:
- Image encryption using advanced algorithms
- Secure image decryption
- Support for saving encrypted/decrypted images
- Visual preview of original and processed images
- User-friendly interface for image manipulation

## Requirements

```python
# Required Python packages
tkinter
PIL (Pillow)
opencv-python (cv2)
numpy
pynput
pyperclip
```

## Installation

1. Clone the repository:
```bash
git clone [repository-url]
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

## Usage

Each tool can be run independently:

```bash
python CaesarCipher.py      # Run the Caesar Cipher tool
python PasswordStrength.py   # Run the Password Strength Checker
python KeyLogger.py         # Run the Keylogger
python PixelManipulation.py # Run the Image Encryption tool
```

## Security Notice

⚠️ **Important**: These tools are for educational and testing purposes only. Please ensure you:
- Have proper authorization before using the keylogger
- Use secure channels when handling encrypted data
- Do not use these tools for malicious purposes
- Keep encrypted files and passwords in secure storage

## Features

- Modern and intuitive graphical user interfaces
- Real-time processing and feedback
- File saving capabilities
- Error handling and user input validation
- Cross-platform compatibility

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Disclaimer

This software is provided for educational purposes only. Users are responsible for complying with applicable laws and regulations regarding the use of these tools. 