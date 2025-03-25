# IoT Device Security Analysis — No Installations Required 🚨

This is a quick, practical analysis of IoT device security using only built-in tools. No installations are required, making it accessible for anyone interested in cybersecurity!

---

## 📌 Project Overview
This project focuses on identifying vulnerabilities in IoT devices using basic network commands. The goal is to assess potential risks and suggest quick security improvements.

---

## 🔧 Steps to Analyze IoT Device Security

1. **Identify Device IP:**  
   - Open the Command Prompt or Terminal.  
   - Type the following command to check the network configuration:  
     ```
     ipconfig (Windows) or ifconfig (macOS/Linux)
     ```  
   - Ping the network to find connected devices:  
     ```
     ping 192.168.1.255
     ```

2. **Check Open Ports:**  
   - In the Command Prompt or Terminal, check open ports:  
     ```
     netstat -an (Windows) or netstat -an | grep LISTEN (macOS/Linux)
     ```  
   - Common risky open ports: **21 (FTP)**, **23 (Telnet)**, **80 (HTTP)**

3. **Analyze Network Traffic:**  
   - View active network connections to check for unusual activity:  
     ```
     netstat -b (Windows) or lsof -i -P (macOS/Linux)
     ```

4. **Search for Vulnerabilities:**  
   - Use Google to search for default credentials:  
     ```
     "<Device Model> default password"
     ```  
   - Check for known vulnerabilities on CVE Details:  
     [CVE Details](https://www.cvedetails.com/)

5. **Test Default Credentials:**  
   - Access the device’s IP in a web browser:  
     ```
     http://<IoT_Device_IP>
     ```  
   - Try common defaults like **admin/admin** or **admin/password**.

---

## 🔐 Security Recommendations
- **Update Firmware:** Ensure the latest firmware is installed.  
- **Strong Passwords:** Change default credentials to strong, unique passwords.  
- **Network Segmentation:** Separate IoT devices on a dedicated network.  
- **Disable Unnecessary Services:** Turn off Telnet, FTP, or HTTP if open.  
- **Regular Monitoring:** Periodically check open ports and network traffic.

---

## 💡 Conclusion
This quick analysis is a starting point for IoT security awareness. For more advanced assessments, consider using specialized cybersecurity tools.

---

### 📩 Connect with Me
- [LinkedIn](https://www.linkedin.com/in/rashida-alexander)   
- [YouTube](https://www.youtube.com/@AR.TECHTALK)

🔗 **Author:** RASHIDA ALEXANDER 
#Cybersecurity #IoTSecurity #EthicalHacking 
