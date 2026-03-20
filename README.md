# 🚀 RushKart AI  
### AI-Powered Parametric Insurance for Delivery Partners  

> Predict disruptions. Protect earnings. Pay instantly.

---

## 📌 Overview  
RushKart AI is an AI-driven parametric insurance platform designed to protect delivery partners from income loss caused by disruptions such as weather, pollution, and traffic.

It combines **AI prediction, real-time monitoring, and automated payouts** to ensure financial stability for gig workers.

---

## ❗ Problem Statement  
Delivery partners lose up to **20–30% income** due to:

- 🌧 Heavy rain / flooding  
- 🌡 Extreme heat  
- 🌫 High AQI  
- 🚧 Traffic disruptions  

Current issues:
- ❌ No income protection  
- ❌ No instant payout system  
- ❌ No predictive intelligence  

---

## 💡 Solution  
RushKart AI introduces a **Hybrid Parametric Insurance Model**:

### 🔹 Automated Parametric Layer  
- Detects disruptions via APIs  
- Auto-triggers claims  
- Instant payouts  

### 🔹 AI Claim Intelligence Layer  
- Chat-based reporting  
- NLP-based validation  
- Proof verification  

---

## ⚙️ System Workflow  

```mermaid
flowchart TD

A[Partner Goes Online] --> B[AI Risk Engine]
B --> C[Weekly Policy Assigned]

C --> D[Monitoring System]
D --> E{Disruption?}

E -->|Yes| F[Trigger Activated]
F --> G[Auto Claim]
G --> H[Instant Payout]

E -->|No| I[User Chat Claim]
I --> J[Upload Proof]
J --> K[AI Validation]

K --> L{Valid?}
L -->|Yes| H
L -->|No| M[Reject]

K --> N[Fraud Detection]
N --> K

H --> O[Dashboard]
M --> O
