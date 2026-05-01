# **OSINT and Recon Lab Report**

## **🔹 1\. Subdomain Enumeration**

**Tool Used:** Recon-ng  
 **Module:** hackertarget  
 **Target Domain:** example.com

---

### **⚙️ Commands Used**

recon-ng  
workspaces create lab1  
workspaces select lab1  
marketplace install all  
modules load recon/domains-hosts/hackertarget  
options set SOURCE example.com  
run  
show hosts  
---

### **📊 Results**

| Subdomain | IP Address | Notes |
| ----- | ----- | ----- |
| example.com | 104.20.23.154 | Main domain |
| [www.example.com](http://www.example.com) | 104.18.27.120 | Web server |

---

### **🧠 Analysis**

The enumeration identified the primary domain and its www subdomain. Since example.com is a reserved domain, only minimal infrastructure is exposed. This demonstrates how reconnaissance tools behave when limited public data is available.

---

## **🔹 2\. Shodan Analysis**

**Tool Used:** Shodan  
 **Query Used:** `example.com`

---

### **⚙️ Steps Performed**

1. Opened Shodan website  
2. Entered search query:

example.com

3. Analyzed exposed servers and services

---

### **📊 Observations**

* Total results: **242,452+ hosts**  
* Identified servers across multiple countries (USA, Germany, China, etc.)  
* Example exposed service:  
  * **Proxmox Virtual Environment server**  
  * Public HTTP response visible  
  * Login panel exposed  
  * Server metadata disclosed (headers, software info)

---

### **📊 Summary (50 Words)**

Multiple internet-facing systems associated with the query were identified using Shodan. Several servers expose web interfaces and service banners, revealing software details and configurations. Some hosts display login portals and metadata, increasing the attack surface. Such exposure may assist attackers in reconnaissance and identifying potential vulnerabilities.

---

## **🔹 Conclusion**

This lab demonstrated the use of Recon-ng and Shodan to gather information about target systems. While subdomain enumeration showed limited results due to the nature of the domain, Shodan revealed a large number of exposed services, highlighting how publicly accessible systems can increase security risks.

