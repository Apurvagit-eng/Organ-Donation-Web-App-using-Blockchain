# Organ Donation Management System using Blockchain and LSTM

## 📌 Project Overview
This project improves transparency and efficiency in organ donation by using blockchain for secure data storage and LSTM (deep learning) for smart matching.

## 🔧 Technologies Used
- **Python** (Flask)
- **Solidity** (Ethereum smart contracts)
- **TensorFlow/Keras** (LSTM model)
- **Web3.js**, **MetaMask**
- **Ganache**
- **HTML/CSS/JavaScript**

## ⚙️ Workflow
1. Donor/receiver registers via web form.
2. Hospital verifies the request.
3. Verified donor info goes to blockchain.
4. Receiver info is matched via LSTM.
5. Match = notify hospital; No match = waitlist.

## 📁 Structure
```
Organ_Donation_Blockchain_Project/
├── frontend/
├── backend/
├── blockchain/
├── models/
├── static/
├── templates/
└── README.md
```

## 🚀 How to Run
1. Install: `pip install flask tensorflow`
2. Run Ganache & deploy smart contract
3. Start Flask: `python backend/app.py`
4. Access frontend via browser

## 👤 Author
Developed as an academic project using Python, ML, and blockchain.
