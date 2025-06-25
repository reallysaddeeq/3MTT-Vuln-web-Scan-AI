# 📌 3MTT Knowledge Showcase Project - Website Vulnerability Assessment with AI

## 👋 About This Project

Did you know that thousands of websites are hacked every day due to hidden vulnerabilities?  
As a **3MTT Cohort 3 Cybersecurity student from Niger State**, I built this project to demonstrate how beginners can use **open-source tools** and **AI** to detect and understand security weaknesses easily.

This project shows:
- How to run a basic website vulnerability scan using **Termux** and **Nikto** on a smartphone.
- How to use **ChatGPT AI** to explain complex scan results in simple language.
- How AI can help automate and simplify security learning.

## ⚙️ Tools Used

- **Termux** (Linux terminal emulator for Android)  
- **Nikto** (Open-source web vulnerability scanner)  
- **ChatGPT AI** (for explaining and fixing vulnerabilities)

## 🛠️ How to Reproduce

1. Install Termux on your phone (from F-Droid).
2. Run these commands:
   ```bash
   pkg update && pkg upgrade
   pkg install perl
   pkg install git
   git clone https://github.com/sullo/nikto.git
   cd nikto/program
   perl nikto.pl -h http://testphp.vulnweb.com

3. Copy the scan output.

4. Paste it into ChatGPT and ask for:

> You are a cybersecurity advisor. Explain this scan output for a beginner and suggest how to fix the issues.

🤖 How AI Helps

In this project, AI (ChatGPT) turns technical scan data into easy-to-understand explanations and recommended fixes.
This makes cybersecurity skills accessible even to beginners with no deep background.

## 🎥 Video Submission

📎 Watch the full video here: [Click to Watch](https://drive.google.com/file/d/19aDoyezgivGKQLwNT_KJNgTDnk2SgmMC/view?usp=drivesdk)

🙌 Acknowledgements

Special thanks to:

3MTT Nigeria

Darey.io

Musab Mubarak (Instructor)

My State Community Manager

📢 Fellow Info

ABUBAKAR AHMADU 
3MTT Cohort 3 Cybersecurity Student — Niger State
Fellow ID: FE/23/25899977

#3MTTLearningCommunity
#My3MTT
@3MTTNigeria

✅ Disclaimer

This project is for educational purposes only.
Always scan and secure websites you own or have permission to test.
