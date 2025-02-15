
# AESCrypto

This project is a **secure and user-friendly** AES encryption and decryption tool, allowing users to **encrypt** and **decrypt** text and files using the **Advanced Encryption Standard (AES)** algorithm.

## Features

- **AES Encryption:** Encrypt text or files using a secret key to protect sensitive data.
- **AES Decryption:** Decrypt encrypted messages or files with the correct key.
- **Support for Multiple AES Key Sizes:** Choose **128-bit, 192-bit, or 256-bit** encryption.
- **Fast & Secure:** Real-time encryption and decryption without compromising security.
- **User-Friendly Interface:** Simple and intuitive web UI for easy use.
- **No Data Storage:** The website does not store any encrypted or decrypted data.
- - **Shows Steps:** The website shows steps for encryption and description.

## How It Works

1. Enter the **text or upload a file** you want to encrypt.
2. Select the **AES encryption key size** (128-bit, 192-bit, or 256-bit).
3. Click **"Encrypt"** to generate a secure encrypted output.
4. To decrypt, enter the **encrypted text** or upload an encrypted file.
5. Enter the correct **key** and click **"Decrypt"** to retrieve the original data.

## Technologies Used

- **Python & Flask** – Backend logic for encryption and decryption.
- **JavaScript & HTML/CSS** – Frontend for a user-friendly interface.


## Installation & Setup

### 1. Clone the Repository

```sh
git clone git@github.com:EnjyRamadan/AESCrypto.git
```

### 3. Run the Application

```sh
python routes.py
```


The website will be available at `http://localhost:5000`.

## Security Considerations

- Always use a **strong encryption key**.
- Never share your encryption key with unauthorized users.
- This tool does **not store** encrypted or decrypted data.
- Ensure you **keep a backup** of your original data before encryption.



