# Pet Feeder Project

## 📖 Overview
This project focuses on building an affordable **automated pet feeder** designed for animal shelters.  
The system:
- Dispenses food at preset times  
- Tracks consumption with weight sensors  
- Issues alerts if food is left uneaten or the supply runs low  

The goal is to provide **reliable feeding while reducing the need for constant human involvement**.

---

## ✨ Key Features
- Scheduled feeding managed by a real-time clock  
- Servo-driven food dispensing mechanism  
- Monitoring of food levels and bowl weight  
- Alerts through LEDs, buzzers, or notifications  
- Manual feeding option  
- Clean, modular, and well-documented code  

---

## ⚙️ System Components
**Inputs:**  
- Feeding schedule  
- Food-level sensor (binary)  
- Bowl weight sensor  

**Outputs:**  
- Servo motor  
- LED/Buzzer alerts  
- LCD display  

**Hardware:**  
- Arduino for core control  
- Raspberry Pi for advanced tasks (camera, email notifications)  

---

## 🛠️ Project Workflow
1. **Step1_Analysis** – System diagrams and overview  
2. **Step2_Datatable** – Inputs, outputs, example values, and constraints  
3. **Step3_Flowchart** – Visual representation of the algorithm  
4. **Step4_WordCode** – Detailed step-by-step algorithm  
5. **Step5_Testing_Refinement** – Sample test cases, outcomes, and improvements  

---

## 🔄 Operational Logic
1. Initialize components (clock, servo, sensors)  
2. Verify feeding schedule or manual request  
3. Check food availability  
4. Dispense food and log bowl weight  
5. Monitor consumption over time  
6. Detect changes in bowl weight and issue alerts if needed  
7. Return to standby mode  

---

## ✅ Test Cases & Results
- Scheduled feeding with pet eating: **Pass**  
- Scheduled feeding without pet eating: **Pass**  
- Servo malfunction: **Fail** (needs improvement)  
- Manual feeding request: **Pass**  
- Empty food bin: **Pass**  

---

## 🚀 Recommended Enhancements
- Adaptive thresholds for different pet sizes  
- Multiple weight checks at intervals  
- Camera or motion sensor integration  
- Cloud-based data logging and alerts  
- Backup power support  
- Smart feeding schedules using machine learning  

---

## 🤖 AI Contribution
Microsoft Copilot supported the project by:  
- Refining the algorithm  
- Suggesting better error handling and alert mechanisms  
- Guiding hardware integration  
- Improving documentation and modular coding practices  

---

## 👤 Author
**Md Amirul Islam Chowdhury**  
- 🎓 Student ID: `u3312674`  
- 📧 Email: `u3312674@uni.canberra.edu.au`  
