# **SOCIAL ENGINEERING LAB REPORT**

## **🔹 1\. Objective**

To simulate a social engineering scenario by gathering phone-based intelligence using OSINT techniques and demonstrating a controlled vishing/pretexting approach.

---

## **🔹 2\. Tools Used**

* Social-Engineer Toolkit (SET)  
* PhoneInfoga  
* Maltego (conceptual mapping)

---

## **🔹 3\. Target Information**

* **Target ID:** TID001  
* **Phone Number:** \+919025818028  
* **Type:** Self (Controlled Environment)

---

## **🔹 4\. Intel Gathering (PhoneInfoga Results)**

| Target ID | Data Source | Information | Notes |
| ----- | ----- | ----- | ----- |
| TID001 | PhoneInfoga | \+91902XXXXX | Self test number |
| TID001 | PhoneInfoga | Country: India | Detected automatically |
| TID001 | PhoneInfoga | Local: 0902XXXXX | Number formatting |
| TID001 | PhoneInfoga | OSINT Links Generated | Google dorking results |

---

## **🔹 5\. Relationship Mapping (Maltego – Conceptual)**

Due to limited public OSINT data, automated relationships were not identified. A conceptual relationship mapping was created:

Phone Number → Test User → Individual → Mobile Device

This represents entity relationships typically visualized using Maltego.

---

## **🔹 6\. Vishing Simulation**

A mock vishing scenario was conducted in a controlled environment using the tester’s own phone number.

**Script Used:**

“Hello, this is from mobile network support. We detected unusual activity on your number. Can you confirm your registered name?”

No real target was involved.

---

## **🔹 7\. SET Tool Usage**

The Social-Engineer Toolkit (SET) was launched and explored. Various social engineering attack vectors, including website-based attacks, were reviewed. This demonstrated how phishing and credential harvesting attacks can be simulated in controlled environments.

---

## **🔹 8\. Summary** 

This lab demonstrated a controlled social engineering simulation using a personal phone number. PhoneInfoga identified number format, country, and generated OSINT links. No additional public data was found. A vishing scenario was safely tested, highlighting reconnaissance methods, privacy awareness, and ethical considerations in social engineering practices.

