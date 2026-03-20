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

### ⚡ Automated Parametric Layer  
- Detects disruptions via APIs
- Detects disruption thresholds
- Auto-triggers claims  
- Instant payouts  

### 🤖 AI Claim Intelligence Layer  
- Chat-based claim reporting 
- NLP-based validation  
- Proof verification
- Prevents fraud and false claims

🧩Rushkart Ecosystem (Simulation Platform): <br>
-A simulated delivery platform built to demonstrate real-world integration.
                
- Go online                    - AI Risk Engine Activate
- Accept Order                 - Real-time Monitoring Starts
- Enter Delivery Zone          - Hyperlocal Risk Analysis
- View Dashboard               - Insurance Insights Displayed

📱Features: <br> Delivery-Time Risk Intelligence: <br><br>
🟢 When Partner Goes Online.
- AI assigns profile.
- Weekly insurance policy activated.
 <br> 
🌦 Real-Time AI Suggestions: <br>
- "Heavy rain expected in your zone in 1 hour" <br>
- "High traffic --> lower delivery efficiency" <br>
- "Switch zone to maximize earnings" <br>
- "Upgrade coverage for Rs5 this week" <br>
<br>
💬 AI Claim System: <br> -Used when system misses disruption: <br>
1. User reports via chat <br>
2. Uploads proof 📸  <br>
3. AI validates: <br>
           💠NLP understanding.<br>
           💠Location match.  <br>
           💠Proof authenticity.
<br> <br>
🎯Results: <br>
 ✅ Claim Approved → Instant payout. <br>
 ❌ Claim Rejected → Fraud prevention.
<br> <br>
🛡 Fraud Detection System: <br>
-📍GPS spoof detection <br>
-🔁Duplicate claim prevention <br>
-🧠Behavioral anomaly detection <br>
-📸Image Proof validation 
<br> <br>

🧱 Tech Stack: <br> 
🧠 AI/ML <br>
-Python (Scikit-learn, TensorFlow) <br>
-NLP Models <br>
-Anomaly Detection 

🌐 Backend <br>
-Node.js / FastAPI <br>
-REST APIs

📱 Frontend <br>
-React / Flutter

🔗 Integrations 
-Weather API <br>
-AQI API <br>
-Traffic APIs (Mock) <br>
-Razorpay (Sandbox) <br>

☁️ Infrastructure <br>
-AWS / GCP <br>
-Firebase <br>
-Docker <br>

🌟 Unique Value Proposition: <br>
  ⚡ Fully automated insurance  <br>
  🤖 AI fallback claim validation  <br>
  📍 Hyperlocal intelligence  <br>
  🔮 Predict-before-loss system  <br>

🚀 Future Scope: <br>
-Real delivery platform integrations  <br>
-Computer vision validation  <br>
-Blockchain-based claims  <br>
-Nationwide scaling

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




