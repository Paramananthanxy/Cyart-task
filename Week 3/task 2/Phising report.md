## **Phishing Simulation Report (Short)**

### **Objective**

To simulate a phishing attack and capture user credentials in a controlled lab environment.

---

### **Tools Used**

* Gophish  
* MailHog  
* Kali Linux

---

### **Methodology**

* Configured Gophish and SMTP (MailHog)  
* Created phishing email template  
* Built fake login landing page with credential capture  
* Launched campaign targeting test user

---

### **Results**

| Timestamp | IP Address | Username | Password | Risk |
| ----- | ----- | ----- | ----- | ----- |
| 2026-04-28 20:53 | 127.0.0.1 | rambo123 | rambo | High |

---

### **Observation**

The phishing attack successfully captured both username and password after fixing the input field configuration.

---

### **Recommendation**

* Enable MFA  
* Conduct user awareness training  
* Use email security filters

---

### **Conclusion**

The simulation demonstrates how phishing attacks can effectively compromise user credentials through social engineering.

