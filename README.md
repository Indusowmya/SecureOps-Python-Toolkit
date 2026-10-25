# SecureOps — Python Security & Data Utility Toolkit

SecureOps is a Python desktop application built with Tkinter. It combines file analysis, CSV management, encrypted local storage, and interactive stack and queue visualization.

## Features

### 1. File Intelligence
- Analyze supported text, log, and CSV files.
- Use multithreading for file analysis.
- Extract useful text and file statistics.

### 2. CSV Manager
- Create and open CSV files.
- View tabular data.
- Add, edit, and delete rows.
- Save changes to CSV files.

### 3. Secure Vault
- Store records in an encrypted local vault.
- Derive encryption keys using PBKDF2-HMAC-SHA256.
- Unlock and lock the vault.
- Add, view, and delete stored records.

### 4. Stack & Queue Lab
- Visualize stack and queue operations.
- Perform stack push and pop operations.
- Perform queue enqueue and dequeue operations.

## Technologies
- Python
- Tkinter / ttk
- CSV and JSON
- Threading and queue
- Regular expressions
- Cryptography (Fernet)

## Requirements
- Python 3
- `cryptography`

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the desktop application:

```bash
python secureops.py
```




