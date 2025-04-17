# 🔐 Secure Data Encryption App

Welcome to the **Secure Data Encryption App**, a user-friendly Streamlit application for securely storing and retrieving sensitive data using encryption.

## 🎯 Features

- **Encrypt Data**: Securely encrypt your data with a custom passkey.
- **Decrypt Data**: Retrieve and decrypt your data with the correct passkey.
- **Passkey Hashing**: Ensures secure validation without storing plaintext passkeys.
- **Reauthorization**: Protects against brute-force attempts with a login feature.
- **Secure Storage**: Encrypted data is safely stored in a JSON file.

![App Demo](https://via.placeholder.com/800x400.gif)  
*Illustration of the app in action.*

---

## 📂 File Structure

- **`main.py`**: Contains the main application code.
- **`secret.key`**: Stores the encryption key (auto-generated).
- **`data.json`**: File for securely storing encrypted data.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- Streamlit library
- Cryptography library

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sana575/secure-data-encryption-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd secure-data-encryption-app
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:
   ```bash
   streamlit run main.py
   ```

---

## 🧩 How It Works

### 1. Home
Provides an overview of the application and its capabilities.

### 2. Store Data
- Enter a **label** and your **data**.
- Set a secure **passkey** for encrypting the data.
- Data is securely stored and encrypted.

### 3. Retrieve Data
- Provide the **label** and correct **passkey**.
- The app decrypts and displays your data.

### 4. Login
- If login is required, enter the **master password** (default: `admin123`) for reauthorization.

---

## 🔧 Customization

You can customize the following in `main.py`:
- **Master Password**: Modify the default password for reauthorization.
- **Encryption Key Location**: Change the `KEY_FILE` path.
- **Data File Location**: Update the `DATA_FILE` path.

---

## 👩‍💻 Author

- **Name**: Sana Ishaq
- **GitHub**: [sana575](https://github.com/sana575)

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 🤝 Contributions

Contributions are welcome! Feel free to fork this repository, create a branch, and submit a pull request.

