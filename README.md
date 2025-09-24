# phishing-email-analysis-task
# Internship Task – Email Analysis  

This repository contains my internship task submission where I analyzed a suspicious email file (`sample-100.eml`).  

---

## 📌 Objective  
The goal of this task was to:  
- Extract key metadata (sender, subject, IP, etc.)  
- Verify SPF, DKIM, and DMARC results  
- Analyze the email body content  
- Identify signs of phishing or spam  

---

## 📂 Files in This Repository  
- `sample-100.eml` → Original email file provided for analysis  
- `Email_Analysis_Report.md` → Detailed report in Markdown format  
- `Email_Analysis_Report.pdf` → Report in PDF format  
- `Email_Analysis_Report.docx` → Report in Word format  

---

## 📝 Summary of Findings  
- The email pretends to be a **solar panel promotion**.  
- Authentication (SPF/DKIM/DMARC) **failed**.  
- Contains **suspicious links** that don’t match the sender’s domain.  
- Uses **urgency and financial bait** (“Save hundreds of euros!”).  
- ✅ **Conclusion:** Likely phishing/spam email.  

---

## 📖 Learnings  
- Gained experience in analyzing raw email headers.  
- Understood how SPF, DKIM, and DMARC checks help identify spoofed emails.  
- Learned to recognize phishing patterns like **fake domains + urgency tricks**.  

---

## 🚀 Next Steps  
- Automate `.eml` parsing using Python (`email` or `mailparser` libraries).  
- Explore tools like **SpamAssassin** or **MISP** for automated phishing detection.  

---

👉 This completes my internship task on **email analysis and phishing detection**.  
