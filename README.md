# MQTT-Based Disaster Relief System: Security & Privacy Analysis

This repository contains two complementary analyses of an MQTT-based disaster relief communication system used by drones, field devices, and cloud components during emergency operations. The project applies both **PASTA** and **LINDDUN** to evaluate the system's security and privacy posture under adversarial conditions.

---

##  PASTA Threat Modelling Analysis

The **Process for Attack Simulation and Threat Analysis (PASTA)** report provides a full risk-centric threat model for the system.

### Highlights
- Seven-stage attacker-driven threat modelling process  
- System architecture decomposition and DFDs  
- Threat enumeration using MITRE ATT&CK, CAPEC, CWE, and CVE  
- Attack simulations (DoS, MITM, credential theft, spoofing)  
- Risk matrix, residual risk calculations, and prioritized mitigations  
- Secure architecture redesign for drones, brokers, dashboards, and cloud components  

### Report
View the full analysis here:  
**`Risk-Centric Threat Analysis of an MQTT-Based Disaster Relief System PASTA.pdf`**

---

##  LINDDUN Privacy Modelling Analysis

The **LINDDUN** report focuses on privacy threats related to the system's data flow and user interactions.

### Highlights
- System-level privacy analysis using the LINDDUN categories  
- Data flow mapping and identification of sensitive assets  
- Privacy threat enumeration (linkability, identifiability, data disclosure, etc.)  
- Motivated attacker analysis and misuse scenarios  
- Privacy-driven mitigation strategies (minimization, unlinkability, integrity protections)  
- Recommendations for user-data handling in crisis environments  

### Report
View the full analysis here:  
**`Ehancing the Privacy of MQTT Disaster Relief Drone Systems LINDDUN.pdf`**


