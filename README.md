**AgriChain – Blockchain-Based Agricultural Supply Chain**

AgriChain is a blockchain-powered solution designed to bring transparency, trust, and fairness to the agricultural supply chain. The platform enables end-to-end tracking of agricultural produce from farmers to consumers while ensuring fair pricing, secure transactions, and verified product quality.

**About the Project**

The agricultural supply chain often lacks transparency, leading to unfair pricing for farmers, delayed payments, and uncertainty for consumers regarding product quality and origin. AgriChain addresses these challenges by leveraging blockchain technology and smart contracts to create a tamper-proof and trustworthy supply chain ecosystem.

By recording every stage of the produce lifecycle on the blockchain, AgriChain ensures accountability, reduces fraud, and builds confidence among farmers, distributors, retailers, and consumers.

**Key Features**

Farmer registration and produce batch creation

Unique batch IDs for every harvest

Smart contracts for automated and timely payments

End-to-end tracking from harvest to retail

On-chain storage of certifications and quality data

QR code-based verification for consumers

Immutable blockchain records to prevent data manipulation

**How It Works**

Farmers register and upload harvest details

Each produce batch is tokenized with a unique ID

Supply chain events such as transport and storage are recorded

Smart contracts manage ownership transfer and payments

Consumers scan QR codes to verify product origin and history

**Technology Overview**

Blockchain with smart contracts for secure data handling

Backend APIs for blockchain interaction

Frontend interface for farmers, distributors, and consumers

On-chain and off-chain data integration for efficiency

**Impact and Benefits**

Ensures fair pricing and timely payments for farmers

Provides consumers with verified and trustworthy product information

Reduces fraud and middlemen involvement

Improves efficiency and accountability in the supply chain

Builds long-term trust across agricultural stakeholders

**Feasibility**

The solution is technically feasible using open-source blockchain frameworks and scalable architectures. It is designed to be adaptable across regions and crops, with a mobile-first approach to support farmers with varying levels of digital access.

**Demo**

Demo Video:



https://github.com/user-attachments/assets/d445449e-9ed1-4f37-80b5-fc5d07347435



<img width="830" height="466" alt="Screenshot 2026-01-30 104918" src="https://github.com/user-attachments/assets/ba0bb306-f0e8-4c9e-9800-80408bd86ac1" />
<img width="827" height="465" alt="Screenshot 2026-01-30 104910" src="https://github.com/user-attachments/assets/a41e63c5-c0dc-4815-b3a6-2872dd52045d" />
<img width="826" height="466" alt="Screenshot 2026-01-30 104859" src="https://github.com/user-attachments/assets/b9e359a2-6e44-4289-b491-44ce5097e8bf" />
<img width="825" height="466" alt="Screenshot 2026-01-30 104848" src="https://github.com/user-attachments/assets/8acdf8a9-5337-4c61-9b4d-2f0f3e058850" />
<img width="828" height="466" alt="Screenshot 2026-01-30 104839" src="https://github.com/user-attachments/assets/feb0183b-1a71-447a-945e-c3e58ccbde75" />



**Conclusion**

AgriChain aims to transform the agricultural supply chain by introducing transparency, security, and trust through blockchain technology. The platform empowers farmers, protects consumers, and promotes a more sustainable and fair agricultural ecosystem.
# How to Run (Reliable Method)

# Terminal 1
```bash
npx ganache-cli --port 7545 --deterministic --networkId 1758369392079
```
# Terminal 2
```bash
npx truffle migrate --reset --network development
node fix-item-tracking.js
```
# Terminal 3
```bash
node server/index.js
```
# Terminal 4
```bash
cd client
npm start
```
