# 📧 Phishing Email Analysis – PayPal Fake Alert

## 🚨 Sample Email:
**From:** service@paypa1.com  
**Subject:** Urgent: Your PayPal Account is Suspended  

Dear User,

We noticed suspicious activity in your account. Your PayPal has been temporarily suspended for your safety.

To restore access, please verify your account immediately:  
[Click here to verify](http://paypal-security-check.com/login)

Failure to do so within 24 hours will lead to permanent suspension.

Thank you,  
PayPal Support Team

---

## 🕵️‍♀️ Phishing Indicators Identified:

| Indicator | Description |
|----------|-------------|
| **1. Spoofed Sender** | Email sent from `paypa1.com` (with the number **1** instead of **l**) instead of official `paypal.com` |
| **2. Urgent Language** | "Failure to do so within 24 hours will lead to suspension" – a pressure tactic |
| **3. Suspicious Link** | `http://paypal-security-check.com/login` is not a real PayPal URL |
| **4. Generic Greeting** | "Dear User" – real services usually use your name |
| **5. Poor Grammar** | Missing article: “Your PayPal has been temporarily suspended” |
| **6. Brand Impersonation** | Email tries to mimic PayPal but uses fake domains and unverified links |

---

## 🛠 Tools Used:
- Google’s [Email Header Analyzer](https://toolbox.googleapps.com/apps/messageheader/)  
- Web browser (for link inspection via hover)  
- Manual review (grammar, structure, and language)

---

## ✅ Conclusion:
This email is a textbook phishing attempt. It uses:
- **Spoofed domains**
- **Urgency**
- **Fake links**
- **Brand impersonation**
to trick users into giving up sensitive information.

Never click such links or enter credentials without checking sender authenticity and link validity.

---

## 📎 Files Included:
- README.md (This analysis)
- phishing_sample.txt (Email content)
