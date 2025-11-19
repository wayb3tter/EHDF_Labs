## **Lab No. 8**

### **Aim**

To understand vulnerabilities found in IT infrastructure and web applications and to identify assessment techniques for both environments.​

### **Theory**

Modern infrastructures comprise physical systems (servers, network equipment), virtual assets (cloud resources), and web-facing services. Each component introduces distinct security risks:

#### **Infrastructure Vulnerabilities**

1. **Hardware Vulnerabilities**:

Found in devices such as network routers, switches, or IoT equipment due to firmware flaws or unpatched systems.​

2. **Configuration Errors**:

Incorrect settings (default credentials, open ports) can expose critical resources to attacks.

3. **Service Vulnerabilities**:

Outdated or misconfigured services (web servers, database servers) provide targets for compromise.

4. **Authentication Weaknesses**:

Poor password practices or lack of multi-factor authentication can increase exposure.

#### **Web Application Vulnerabilities**

1. **Injection Attacks**:

Attacker inserts malicious data (SQL, XML, or code injection) to manipulate or damage a web application.​

2. **Cross-Site Scripting (XSS)**:

Malicious scripts are injected into web pages, compromising clients or stealing information.

3. **Broken Authentication/Session Management**:

Flaws in login mechanisms may allow privilege escalation or unauthorized account access.

4. **Insecure Direct Object References**:

When an application exposes internal implementation objects to the user, attackers may manipulate these to access unauthorized data.​

5. **Security Misconfiguration**:

Default settings, exposed cloud storage, or improper access permissions can invite attacks.

#### **Assessment Techniques**

1. **Network-Based Vulnerability Assessment**:

Scanning infrastructure devices for flaws using automated tools.​

2. **Web Application Vulnerability Scanning**:

Specialized tools (e.g., OWASP ZAP, Burp Suite) identify issues in web apps by simulating user and attacker interactions.​

3. **Penetration Testing**:

Involves probing both network infrastructure and applications to discover and demonstrate exploitability of real-world weaknesses.​

4. **Secure Coding and Review**:

Reviewing code and application logic for security best practices (OWASP Top Ten guidance).​

5. **Continuous Monitoring**:

Using intrusion detection/prevention systems and real-time monitoring to catch developing threats.​

Best practices combine automated and manual assessments, post-scan validation, and prioritization based on risk and business impact.
