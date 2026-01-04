# 🎓 Digital Certificate Verifier (Blockchain Powered)

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Solidity](https://img.shields.io/badge/Solidity-%5E0.8.0-363636.svg)
![Ethereum](https://img.shields.io/badge/Network-Sepolia%20Testnet-lightgrey.svg)

## 🚀 About The Project
This is a **Decentralized Application (dApp)** that eliminates fake degrees and certificate fraud. It uses the **Ethereum Blockchain** to issue immutable, tamper-proof academic records. 

Universities can issue certificates by storing a cryptographic hash of the student's data on-chain. Employers can verify these certificates instantly without needing a middleman.

**🔴 Live Demo:** [Click Here to Verify a Certificate](https://yakshithamydukuri.github.io/certificate-verifier/)  
*(Make sure you have MetaMask installed and connected to Sepolia Network)*

---

## 🛠️ How It Works
The system uses **Keccak-256 Hashing** to secure data.
1.  **Issuance:** The Admin enters Student ID + Course Name. The app generates a unique hash (digital fingerprint) and stores it on the blockchain.
2.  **Verification:** Anyone can enter the student's details. The app regenerates the hash and checks the blockchain ledger.
3.  **Result:**
    * ✅ **Match:** The certificate is authentic.
    * ❌ **No Match:** The certificate is fake or tampered with.

---

## ✨ Key Features
* **Immutability:** Once a certificate is issued, it cannot be deleted or altered.
* **Decentralized:** No central server; runs entirely on the Ethereum network.
* **Instant Verification:** Verifies authenticity in milliseconds.
* **Admin Security:** Only the University (Contract Owner) can issue certificates.
* **PDF Generation:** Successfully verified students can download an official PDF.

---

## 💻 Tech Stack
* **Smart Contract:** Solidity (v0.8.0)
* **Frontend:** HTML5, CSS3 (Glassmorphism UI), JavaScript
* **Blockchain Interaction:** Ethers.js
* **Tools:** Remix IDE, MetaMask, GitHub Pages

---

## 📸 Screenshots
*(You can add screenshots of your project here later!)*

---

## 🏗️ How to Run Locally
1.  Clone the repository:
    ```bash
    git clone [https://github.com/yakshithamydukuri/certificate-verifier.git](https://github.com/yakshithamydukuri/certificate-verifier.git)
    ```
2.  Open `index.html` in your browser (use VS Code Live Server for best results).
3.  Connect MetaMask to **Sepolia Testnet**.
4.  Start verifying!

---

**Built with 💙 by Yakshitha Mydukuri**
