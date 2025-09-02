# 🥗 Smart Diet Planner Bot – Dual-Mode Automation 🤖💻  
UiPath | Web Scraping | Automation  

📌 **Overview**  
The **Smart Diet Planner Bot** is an RPA project built with **UiPath Studio** that calculates **BMI** and generates a **personalized diet plan** using **dual automation paths**.  
It combines **logic-driven automation** with **live web scraping** to deliver instant calorie suggestions or real-time meal plans from the web. 🚀  

---

## 🔍 The Problem  
- People often struggle to calculate BMI and design healthy diet plans.  
- Searching online for calorie-based meal suggestions takes time and effort.  
- Existing tools lack automation for quick, accurate, and personalized results.  

---

## 💡 The Solution  
This bot solves the challenge by:  
1️⃣ Capturing user details (Name, Weight, Height)  
2️⃣ Calculating BMI dynamically  
3️⃣ Offering **two smart automation modes**:  
   - ⚡ **Automated Mode** → Quick, logic-based calorie & meal recommendations  
   - 🌐 **Web Scraping Mode** → Real-time diet plan fetched from *Eat This Much*  
4️⃣ Supporting multiple sessions with seamless user interaction  
5️⃣ Delivering personalized, accurate, and time-saving results  

---

## 🛠️ How It Works  

1. 🧑‍💻 **Input Dialogs** capture Name, Weight, Height  
2. 🧮 **BMI Formula** → `BMI = weight / (height/100)^2`  
3. 🔀 **Decision Handling** → Flowchart branches into modes  

### ⚡ Automated Mode  
- Categorizes BMI: Underweight, Normal, Overweight, Obese  
- Suggests calorie intake & meals instantly via Message Boxes  

### 🌐 Web Scraping Mode  
- Opens browser → navigates to *Eat This Much*  
- Inputs calorie values automatically:  
  - Underweight → **3000 cal**  
  - Normal → **2000 cal**  
  - Overweight → **1500 cal**  
  - Obesity → **1000 cal**  
- Scrapes meal suggestions dynamically and presents them to the user  

---

## ⚙️ Tech Stack & Activities Used  
- **UiPath Studio** 🤖  
- Key Activities:  
  - Input Dialog  
  - Assign (BMI calculation)  
  - If / FlowDecision  
  - Message Box  
  - Open Browser / Type Into / Click / Scroll (web scraping)  
  - Flowchart for branching workflows  

---

## 📊 Output  
- **Automated Mode** → On-screen recommendations (calories & meal plan)  
- **Web Scraping Mode** → Real-time meal plan displayed from the website  

---

## 🚀 Impact  
- ⏳ Saves time compared to manual BMI and diet planning  
- ✅ Provides accurate recommendations tailored to BMI  
- 🌐 Enables live, web-based diet planning using automation  
- 🔄 Demonstrates the **power of dual-mode automation** in RPA  

---

## 🌟 Key Learnings  
- Built **multi-path workflows** in UiPath  
- Blended **logic-driven automation** with **dynamic web scraping**  
- Mastered **browser automation & selectors**  
- Showcased how RPA can improve **personal health management**  

---

## ▶️ How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/Yours-Nishant/Diet_Panner.git
   ```
2. Open Main.xaml in UiPath Studio
3. Install dependencies:
   - UiPath.Excel.Activities
   - UiPath.System.Activities
   - UiPath.UIAutomation.Activities
   - UiPath.WebAPI.Activities
4. Run the workflow
5. Choose either Automated Mode or Web Scraping Mode

Get your personalized diet plan instantly 🎯
