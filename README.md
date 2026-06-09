Password Cracking and Hashing Algorithms 🔐
Hashing Project Banner

🛡️ Password Cracking & Hashing Algorithms 🚀
Learn, implement, and test password security algorithms in Python! ⚡
Covers MD5, SHA-256, SHA-512, bcrypt, salting, and password cracking (dictionary & brute force).
Tech Stack: Python, Hashlib, Bcrypt, Pytest

🧠 Introduction
Developed as part of my internship with Codec Technologies, this project provides hands-on implementations of password hashing & cracking techniques.
It demonstrates secure hashing (with & without salting) and showcases how password cracking is attempted using brute force and dictionary attacks.

📦 Features
🔒 Hashing Algorithms – MD5, SHA-256, SHA-512, bcrypt
🧂 Salting – Protect against rainbow table attacks
🪓 Password Cracking – Brute-force & dictionary-based methods
📂 Examples Included – Easy-to-run demo scripts
🧪 Unit Tests – Verify correctness of hashing & cracking functions
📝 Well-Structured Project – Clean and modular codebase
🛠️ Technologies Used
Python Bcrypt Pytest

🚀 How to Run the Project?
✅ Prerequisites:
Python 3.8+
Virtual environment (recommended)

# Install dependencies
pip install -r requirements.txt

# Run example scripts
python -m examples.demo_hashing
python -m examples.demo_salting
python -m examples.demo_cracker
🗂️ Project Structure
Password-Cracking-and-Hashing-Algorithms/
│
├── docs/                             ← Documentation
│   ├── project_overview.md
│   ├── algorithm_explanations.md
│   └── screenshots/
│       ├── hash_demo.png
│       ├── crack_demo.png
│       └── salted_hash.png
│
├── src/                              ← Core Implementation
│   ├── hash_functions.py             ← MD5, SHA256, SHA512, bcrypt
│   ├── salting.py                    ← Salting & secure hashing
│   ├── password_cracker.py           ← Brute force & dictionary attack
│   └── utils.py                      ← Helper functions
│
├── examples/                         ← Demo Scripts
│   ├── demo_hashing.py
│   ├── demo_salting.py
│   └── demo_cracker.py
│
├── tests/                            ← Unit tests
├── requirements.txt                  ← Dependencies
└── README.md
🌟 Key Learnings
Understood password hashing algorithms (MD5, SHA, bcrypt)
Learned how salting enhances password security
Implemented brute force and dictionary cracking in Python
Gained insights into ethical hacking & password protection
Improved debugging and testing skills with Pytest
