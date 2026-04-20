
# HeliosChain

HeliosChain is a consumer-centric smart contract security scanner designed to help retail crypto investors understand the risks hidden inside decentralized finance (DeFi) smart contracts. The platform analyzes contract code, evaluates multiple risk factors, and presents a simplified security score with a plain-language explanation.

The system combines static analysis techniques, economic risk detection, and AI-assisted explanations to transform complex smart contract vulnerabilities into understandable insights for non-technical users.

---

# Tech Stack

| Technology | Layer / Purpose |
|-------------|----------------|
| Next.js | Frontend framework for the web application |
| React | Component-based UI architecture |
| TailwindCSS | Styling framework for responsive UI |
| Recharts | Data visualization for risk dashboards |
| Node.js | Backend runtime environment |
| Express.js | Backend API server |
| MongoDB Atlas | Database for storing scan history and user data |
| Gemini API | Plain-language risk explanation generation |
| Etherscan API | Smart contract source code retrieval |
| Polygonscan API | Smart contract source code retrieval for Polygon network |
| IPFS | Decentralized storage for audit reports |
| Pinata | IPFS pinning and file persistence |

---

# List of Features

- Contract Interceptor (Fetch Smart Contract Source)
- Cryptographic Contract Fingerprinting
- Suspicious Function Name (Obfuscation) Detector
- Smart Contract Complexity Analyzer
- Rug Pull Liquidity Risk Detector
- Multi-Factor Risk Engine
- Gemini AI Plain-Language Risk Summary
- Multi-Factor Risk Visualization Dashboard
- IPFS Audit Report Storage
- Verifiable Audit CID Generation
- Decentralized Scan Certificate
- Public Scan History Dashboard

---

# Development Phases

## Phase 1 — Website Foundation
### Subcomponents
- Landing Page
- FAQ Page
- Login / Signup
- Dashboard Layout
- Sidebar Navigation
- Scan Input UI

## Phase 2 — Contract Interceptor
### Subcomponents
- Smart Contract Address Input
- Explorer API Fetch
- Contract Code Retrieval
- Code Preview Display

## Phase 3 — Security Analysis Engine
### Subcomponents
- Cryptographic Contract Fingerprinting
- Suspicious Function Name Detector
- Smart Contract Complexity Analyzer
- Rug Pull Liquidity Risk Detector
- Multi-Factor Risk Engine

## Phase 4 — AI Explanation and Visualization
### Subcomponents
- Gemini AI Risk Explanation
- Risk Breakdown Charts
- Risk Score Meter
- Risk Analysis Dashboard

## Phase 5 — Decentralized Audit Storage
### Subcomponents
- IPFS Audit Report Storage
- Verifiable Audit CID Generation
- Decentralized Scan Certificate
- Public Scan History Dashboard

---

# Instructions to Run the Repository

## 1. Backend Setup
### Step 1: Open terminal and navigate to backend

cd backend

### Step 2: Install backend dependencies

npm install

### Step 3: Create Environment Variables

Inside the backend folder create a file called:

.env by following the .env.example file


### Step 4: Start the backend server

npm run dev

Expected output:

HeliosChain API running on http://localhost:5000
MongoDB connected

--------------------------------------------------

## 2. Frontend Setup

The frontend is built with:

- Next.js
- React
- TailwindCSS

Open a new terminal window.

### Step 1: Navigate to frontend

cd frontend

### Step 2: Install frontend dependencies

npm install


### Step 3: Start the frontend server

npm run dev

The frontend will start at:

http://localhost:3000

--------------------------------------------------

## 3. ML Scoring Engine 
Access the ML files and notebooks for Hybrid Scoring Engine in ML Folder.

## 4. Smart Contracts
Deploy the smart contracts locally via hardhat scripts for a local setup by your wallet address.

## 5. Verify Installation

1. Open a browser.
2. Visit:

http://localhost:3000

3. The HeliosChain landing page should appear.

---

# Project Recording and Pitch Presentation



---
# Literature Survey and Feature Engineering Reseach

## Datasets
The following datasets were used for training and experimentation.

[Kaggle] SmartBugs Wild Dataset - https://www.kaggle.com/datasets/tranduongminhdai/smartbug-dataset/data

[HuggingFace] Smart Contract Vulnerability Dataset - https://huggingface.co/datasets/darkknight25/Smart_Contract_Vulnerability_Dataset

## Papers Referred

Citation: @inproceedings{liu2021smart,
  title={Smart Contract Vulnerability Detection: From Pure Neural Network to Interpretable Graph Feature and Expert Pattern Fusion},
  author={Liu, Zhenguang and Qian, Peng and Wang, Xiang and Zhu, Lei and He, Qinming and Ji, Shouling},
   booktitle={IJCAI},
  pages={2751--2759},
  year={2021}
}
