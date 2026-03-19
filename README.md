# SurakshaX – AI Digital Twin Insurance for Gig Workers

## About the Project
India’s gig economy powers millions of deliveries every day, yet delivery partners remain financially vulnerable to external disruptions such as heavy rainfall, extreme heat, pollution spikes, and curfews. These events can reduce earnings significantly, often without any safety net.

SurakshaX is an AI-powered parametric insurance platform designed to address this gap. Instead of offering fixed payouts, it creates a digital twin for each worker. This AI model estimates what a worker would have earned in normal conditions and compensates them for the difference.

---

## What Inspired Us
While studying the gig economy, we identified a key limitation in existing insurance systems:

- Traditional insurance compensates based on events  
- Gig workers lose income based on missed opportunities  

This led us to rethink insurance as a system that ensures income continuity using AI-driven predictions.

---

## Core Innovation

### 1. AI Digital Twin
Each delivery partner is associated with a behavioral AI model trained on:

- Working hours  
- Delivery frequency  
- Peak time activity  
- Historical earnings  

When a disruption occurs:
 - Payout = ExpectedIncome_AI - ActualIncome


This ensures fair and personalized compensation for every worker.

---

### 2. Invisible Insurance
The system is designed to eliminate friction:

- No manual claims  
- No forms  
- No delays  

The system automatically:
- Detects disruptions  
- Verifies inactivity  
- Triggers payouts  

This creates a seamless user experience.

---

### 3. Swarm Intelligence Fraud Detection
Unlike traditional systems that detect individual fraud, SurakshaX identifies coordinated fraud networks.

#### Adversarial Defense Strategy

**Real vs Fraud Detection Signals:**
- Movement patterns (continuous vs unnatural)  
- App activity (active vs inactive)  
- Sensor data consistency  
- Historical behavior patterns  

The system flags deviations from normal behavior.

---

#### Advanced Data Signals Used
- Accelerometer and motion data  
- App usage patterns  
- Network signal variations  
- Delivery logs  
- Historical earning trends  
- Time-based behavior  
- Clustered claim patterns  

---

#### Swarm Fraud Detection
- Graph-based clustering  
- Detection of simultaneous claim bursts  
- Identification of location-based anomaly spikes  

The system focuses on detecting fraud ecosystems rather than isolated cases.

---

#### Fairness Layer
To ensure a balanced experience:

- Suspicious claims are soft-flagged  
- Partial payouts are released instantly  
- Remaining amounts are processed after verification  

This prevents delays for genuine users while minimizing fraud risk.

---

## Parametric Trigger System
Claims are triggered automatically when:

- Rainfall exceeds a defined threshold  
- Air quality reaches hazardous levels  
- Temperature crosses safe limits  
- Curfews or zone restrictions are imposed  

The system focuses on income loss rather than physical damage.

---

## Weekly Dynamic Pricing Model

 - Premium = Base + (RiskScore × ExposureHours)


Where:
- RiskScore is based on local disruption probability  
- ExposureHours represent weekly working hours  

Pricing adjusts dynamically based on:
- Location  
- Weather patterns  
- Worker behavior  

---

## Hyperlocal Risk Intelligence
SurakshaX provides a real-time risk heatmap:

- High-risk zones  
- Moderate-risk zones  
- Safe zones  

Workers can use this data to:
- Plan routes  
- Optimize earnings  
- Avoid high-risk areas  

---

## AI/ML Integration
- Income prediction using digital twins  
- Dynamic pricing models  
- Fraud detection systems  
- Cluster-based fraud analysis  
- Predictive disruption modeling  

---

## System Architecture

### Data Layer
- Weather data APIs or simulated data  
- Air quality data  
- User activity simulation  

### AI Layer
- Income prediction models  
- Fraud detection engine  
- Risk scoring system  

### Application Layer
- User onboarding  
- Policy management  
- Claim automation  

### Payment Layer
- Simulated instant payout system  

---
## Tech Stack

### Frontend
- React.js – Interactive user dashboard  
- Tailwind CSS – Clean and responsive UI  
- Chart.js / Recharts – Analytics and risk visualization  

---

### Backend
- Flask  – API and business logic  
- REST APIs – Communication between services  

---

### Database
- MongoDB – Stores user data, policies, and claims  
- Redis  – Used for real-time trigger caching  

---

### AI / ML Layer
- Python (Scikit-learn, Pandas, NumPy)  
  - Digital Twin income prediction  
  - Risk scoring model  

- NetworkX / Graph-based models  
  - Swarm fraud detection using cluster analysis  

---

### Data & APIs
- OpenWeather API  – Weather-based triggers  
- AQI APIs  – Air quality monitoring  
- Simulated delivery data – Worker activity patterns  

---

### Fraud Detection Signals
- Device motion data (simulated)  
- Location behavior patterns  
- Historical activity trends  
- Cluster-based anomaly detection  

---

### Payment Simulation
- Razorpay (test mode) / Stripe sandbox / Mock APIs  
  - Used for instant payout simulation  

---

### Deployment (Optional)
- Vercel / Netlify – Frontend hosting  
- Render / Railway / AWS – Backend deployment  

## Key Features
- AI-driven onboarding and profiling  
- Weekly policy generation  
- Real-time disruption monitoring  
- Automated claim processing  
- Personalized payouts using digital twins  
- Fraud detection using swarm intelligence  
- Hyperlocal risk insights  

---

## Challenges Addressed
- Designing fair AI-based compensation models  
- Detecting advanced GPS spoofing fraud  
- Maintaining a simple user experience with complex backend systems  
- Balancing automation with trust and transparency  

---

## Conclusion
SurakshaX redefines insurance for gig workers. Instead of reacting to events, it predicts income loss and ensures workers are compensated for missed opportunities. It is a proactive financial safety system built on data, intelligence, and fairness.
