# ATM-verification-System-using-python


<div align="center">

#  **ATM PIN Verification System**

###  A Simple & Interactive Gradio Web App Simulating Real ATM PIN Security

🚀 Built entirely with **Python** and powered by **Gradio**, this project simulates a **real ATM PIN verification process**, allowing users **three secure attempts** to enter their PIN before the account is **temporarily locked**.

✨ This project was developed as part of the **AI Now Bootcamp** organized by **The Incubator Hub**, under the guidance of **Mr. Israel Olanrewaju Odeojo** and **Mr. Ezekiel Ogundepo**.

---

🎯 **[👉 Live Demo – Try It Now!](https://your-gradio-demo-link-here)**

---

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![Gradio](https://img.shields.io/badge/Gradio-App-green?logo=gradio)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Status-Active-success)

</div>

---

## 🧠 **Features**

* 🔐 **PIN Verification System** with only 3 allowed attempts
* 🚫 **Automatic account lock** after failed attempts
* 🧮 Uses **loop and conditional logic** to simulate real ATM flow
* 🌐 **Gradio-based web interface** — clean, interactive, and user-friendly
* ⚡ Real-time response for each input attempt
* 🧰 100% **Python-based**, no database required

---

##  **Logic Overview**

| **Condition**     | **Rule**                 | **Action**         |
| :---------------- | :----------------------- | :----------------- |
| PIN correct       | Matches stored PIN       | ✅ Access granted   |
| PIN incorrect     | Up to 3 attempts allowed | ⚠️ Warning message |
| 3 failed attempts | Exceeded maximum tries   | 🔒 Account locked  |

---

## 🧾 **Sample Run**

| Input  | Attempt | Output                                 |
| ------ | ------- | -------------------------------------- |
| `1111` | 1st     | ❌ Incorrect PIN. 2 attempts remaining. |
| `2222` | 2nd     | ❌ Incorrect PIN. 1 attempt remaining.  |
| `1234` | 3rd     | ✅ PIN accepted. Access granted.        |

---

## ⚙️ **Technologies Used**

🧰 **Core Stack**

* 🐍 Python 3.8+
* 🌐 Gradio Framework

🖥️ **Tools**

* Visual Studio Code
* Git & GitHub

---

## 🚀 **Run the App Locally**

Follow these steps to set up and run your ATM system 👇

1️⃣ **Clone this repository**

```bash
git clone https://github.com/yourusername/atm_pin_verification_system.git
cd atm_pin_verification_system
```

2️⃣ **Install dependencies**

```bash
pip install gradio
```

3️⃣ **Run the application**

```bash
python atm_pin_system.py
```

4️⃣ **Open in browser**

```
http://127.0.0.1:7860
```

🎉 Your ATM PIN Verification System is live locally!

## 👨‍💻 **Author**

**Oluyinka Oluwaseun Emmanuel (Crondo)**
📧 [oluyinkaoluwaseun6@gmail.com](mailto:oluyinkaoluwaseun6@gmail.com)
💻 [GitHub Profile](https://github.com/oluwaseun55)
🏙️ Lagos, Nigeria

---

## 🧑‍🏫 **Acknowledgment**

Special thanks to:

* **Mr. Israel Olanrewaju Odeojo**
* **Mr. Ezekiel Ogundepo**
  for their mentorship and guidance at **The Incubator Hub** during the **AI Now Bootcamp**.

---

## 🪪 **License**

This project is licensed under the **MIT License** — free for educational, personal, and open-source use.

---

<div align="center">

> 💡 *“Keep Learning Until You Become It.”*

✨ Developed with ❤️ by **Oluyinka Oluwaseun Emmanuel** ✨
#TheIncubator #AINowBootcamp

</div>

---

Would you like me to generate this as a ready-to-upload `README.md` file (with Markdown formatting intact)?
