# KeyLogger: System Monitoring and Logging Tool

---

## **Overview**
KeyLogger is a Python-based application designed to monitor and log various system activities. This tool demonstrates capabilities like recording keystrokes, capturing clipboard content, gathering system information, and taking webcam snapshots. It serves as an educational project to understand the implementation of logging mechanisms and cryptography.

> **Note:** This tool is for educational purposes only. Unauthorized use of such tools is illegal and unethical.

---

## **Features**

### Logging Capabilities
1. **Keystroke Logging**: Records user keystrokes and encrypts the log.
2. **Clipboard Monitoring**: Captures clipboard content.
3. **System Information Gathering**: Retrieves and stores system details.
4. **Webcam Capture**: Captures images using the system's webcam.

### Encryption
- All logs (e.g., keystrokes, system info) are encrypted to ensure secure storage.

### Output
- Logs and captured data are stored in encrypted files (e.g., `e_key_log.txt`, `e_systeminfo.txt`).

---

## **Prerequisites**

Ensure you have the following installed:
- **Python** (v3.6 or later)
- **pip** (Python package manager)

---

## **Setup Instructions**

### Clone the Repository
```bash
git clone https://github.com/shakthiprasads/Key-Logger.git
cd KeyLogger-main
```

### Install Dependencies
Install the required Python libraries:
```bash
pip install -r requirements.txt
```

### Run the Application
To start the KeyLogger, execute:
```bash
python main.py
```

---

## **Code Dependencies**

The application relies on the following Python libraries:
- **cryptography**: For encrypting logs.
- **pynput**: For capturing keystrokes.
- **platform**: To gather system information.
- **opencv-python**: For accessing the webcam.

For the full list, refer to `requirements.txt`.

---

## **Files and Outputs**
- **`main.py`**: Main script to execute the application.
- **`requirements.txt`**: Contains the list of required dependencies.
- **`e_key_log.txt`**: Encrypted keystroke logs.
- **`e_systeminfo.txt`**: Encrypted system information.
- **`web_camera.png`**: Captured webcam images.

---

## **Disclaimer**
This project is strictly for educational purposes. Misuse of this tool for malicious purposes is against the law. Always ensure you have explicit permission before deploying such tools.

---

## **License**
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

### **Happy Learning!** 🛠️✨
