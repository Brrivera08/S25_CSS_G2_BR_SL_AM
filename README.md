# 🛡️ S25_CSS_G2_BR_SL – Computer Systems Security Project

This project simulates a comprehensive secure access control environment designed to showcase and implement fundamental principles of computer systems security. It goes beyond basic authentication by incorporating multiple layers of protection, including password-based login and multi-factor authentication, ensuring that only authorized users gain access to sensitive resources. The system employs role-based access control (RBAC) to enforce permission boundaries, while also integrating with human resources workflows to manage onboarding, offboarding, and temporary access assignments in a controlled and auditable manner. Additionally, automated monitoring and logging functionalities have been included to provide visibility into access events, allowing for timely detection of suspicious behavior or policy violations. Collectively, these components mirror real-world enterprise-level security infrastructure, making the project a practical and educational demonstration of secure system design.

---

## 🔍 Project Objective

The main goal of this project is to:

- Implement secure **user authentication** with multi-factor support
- Integrate **HR-driven access control** for onboarding/offboarding
- Enable **temporary access roles** with automated expiration
- Provide **alerting and monitoring** of suspicious login activity
- Offer **admin dashboards** for access and alert management

---

## 🚀 Key Features

### 🔐 Authentication System
- Username + password login
- Second-factor verification (2FA) via email tokens
- Password reset with secure token validation

### 🧑‍💼 HR System Integration
- Detect employee offboarding events
- Automatically revoke access upon termination
- HR dashboard to assign temporary access roles (interns, contractors)

### ⏳ Temporary Access Roles
- Admins and HR can assign roles with time-limited access
- System automatically removes expired roles

### 📨 Password Reset & Token Logic
- Tokenized email-based reset links
- Token validation, expiration, and form-based password change
- CAPTCHA and rate-limiting to prevent abuse

### 📊 Security Monitoring & Alerts
- Alert generation for suspicious login attempts
- Admin alert management dashboard with search and filtering
- Alerts logged and actionable (e.g., escalate or acknowledge)

---


## 🛠️ Technologies Used

- **Python 3.11**
- **Flask** (Micro web framework)
- **HTML/CSS/JS** (for UI)
- **smtplib**, **secrets**, **itsdangerous**, **Flask-Limiter**
- Optional: **CAPTCHA API**, **Slack webhook**

## References

- NIST. (2020). Zero Trust Architecture. https://doi.org/10.6028/NIST.SP.800-207
- OWASP. (n.d.). Authentication Cheat Sheet. https://cheatsheetseries.owasp.org
- Flask Documentation. https://flask.palletsprojects.com

---

## 📖 Use Cases

- Demonstrating secure login and 2FA flows  
- Automating HR-driven access removal  
- Managing short-term user access roles  
- Monitoring user behavior and generating alerts  
- Reviewing and escalating alerts via a dashboard

---

## 📚 Documentation

See the [Wiki](https://github.com/Brrivera08/S25_CSS_G2_BR_SL/wiki) for:

- ✅ [User Stories]
- 🔐 [Access Control & Authentication]
- 🚨 [Security Monitoring & Alerts]

---

##  Conclusions

In conclusion, this project successfully demonstrates the implementation of a secure access control system that reflects modern best practices in computer systems security. By integrating multifactor authentication, role-based access control, HR process alignment, and real-time monitoring, the system offers a layered defense approach suitable for enterprise environments. Through the development and simulation of this environment, our team gained valuable insights into the complexities of access management, the importance of security auditing, and the real-world challenges of enforcing least privilege. This project not only reinforced our technical skills in Python and Flask development but also deepened our understanding of the critical role that security protocols play in protecting digital infrastructure.

## 👥 Authors

- @Brrivera08  
- @SethLackey  
- @aamata1  
- Group 2 – S25 CSS Class



