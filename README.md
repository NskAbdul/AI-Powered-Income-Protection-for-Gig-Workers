# 🚀 AI-Powered Income Protection for Gig Workers

## 📌 Inspiration

We noticed that delivery partners (like those working with Zomato or Swiggy) depend completely on daily earnings. If something like heavy rain, extreme heat, or pollution happens, they simply cannot work — and that directly affects their income.

What surprised us was that while many types of insurance exist, there is nothing that protects their **lost earnings due to external conditions**. That gap inspired us to build a solution focused purely on income protection.

---

## 💡 What it does

Our solution is a **parametric insurance platform** designed specifically for gig workers.

Instead of traditional insurance (where users need to file claims), our system works automatically:

- It monitors external conditions like weather and pollution
- When a predefined condition is met (for example, heavy rainfall or very high AQI)
- The system **automatically triggers a claim**
- And the worker receives compensation for lost income

We also designed it with a **weekly subscription model**, since gig workers typically think in weekly earnings rather than long-term policies.

---

## ⚙️ How we planned and designed it

We approached this problem by breaking it into simple steps:

1. A delivery partner signs up and selects a weekly insurance plan  
2. The system calculates a **weekly premium** based on their working area and risk level  
3. External data (weather, pollution, etc.) is continuously monitored  
4. If a disruption occurs, the system automatically:
   - Detects it
   - Calculates the estimated income loss
   - Initiates payout  

We also plan to include:

- **AI-based risk assessment** → to adjust pricing based on location and past data  
- **Fraud detection mechanisms** → to avoid misuse like fake claims or location spoofing  

---

## 💰 Weekly Pricing Model

We kept the pricing simple and practical.

Weekly Premium = Base Price + Risk Factor

Example:
- Base price: ₹20/week  
- High rainfall area: +₹10  
- High pollution area: +₹5  

Final premium = ₹35/week  

This ensures affordability while still reflecting real-world risk.

---

## ⚡ Parametric Triggers

Instead of manual claims, we use event-based triggers:

- Heavy Rain → Rainfall above threshold  
- Extreme Heat → Temperature above safe limit  
- Pollution → AQI above critical level  
- Curfew → Restricted movement in area  

When these happen, payouts are triggered automatically.

---

## 🧠 AI Integration (Planned)

We plan to use AI in two main areas:

1. **Risk Prediction**
   - Adjust premium based on location and historical data  

2. **Fraud Detection**
   - Detect unusual claim patterns  
   - Prevent duplicate or false claims  

At this stage, we have designed the logic and workflow for these components.

---

## 🛠️ Tech Stack

We chose a simple and scalable stack:

- Frontend: React.js  
- Backend: FastAPI (Python)  
- Database: MongoDB  
- AI/ML: Python (Scikit-learn)  
- APIs: Weather & Pollution (real or mocked)

This allows us to easily integrate AI and real-time data in later phases.

---

## 🚧 Challenges we identified

- Defining fair and realistic trigger conditions  
- Designing a pricing model that is both affordable and sustainable  
- Preventing fraud in an automated system  
- Simulating real-world conditions in early stages  

---

## 🏆 What we are proud of

- A clear and practical solution for a real-world problem  
- Fully automated claim process (no manual steps)  
- Weekly pricing model aligned with gig workers  
- Strong foundation for AI-based improvements  

---

## 📚 What we learned

- How parametric insurance works in real scenarios  
- The importance of designing for user behavior (weekly income mindset)  
- How AI can be applied beyond just predictions — into real systems  
- Thinking from both user and business perspectives  

---

## 🔮 What’s next

In the upcoming phases, we plan to:

- Build the working prototype  
- Integrate real-time APIs  
- Implement dynamic pricing using ML  
- Add instant payout simulation  
- Develop a dashboard for users and admins  

---

## ✅ Summary

Our goal is simple:  
To create a safety net for gig workers so that external disruptions don’t completely affect their livelihood.

We believe this solution can make gig work more stable and secure.
