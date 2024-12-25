# CODTECH-TASK-02

**Name:** SHASHANK SATISH MISHRA

**Company:** CODTECH IT SOLUTIONS PVT. LTD

**ID:** CT0806DB

**Domain:** CYBER SECURITY AND ETHICAL HACKING

**Duration:** 3 WEEKS

**Mentor:** NEELA SANTOSH KUMAR

# Overview of the project

# Project: Vulnerability Scanning Tool

### Project Overview: Vulnerability Scanner Tool

This project is a **GUI-based web vulnerability scanner** designed to identify if a web server's directory listing feature is unintentionally enabled. Directory listing is a misconfiguration where the server displays the contents of a directory if no index file (e.g., `index.html`) is present. This can expose sensitive data or files that could be exploited by malicious actors. The tool provides an easy-to-use interface for users to perform this check without requiring deep technical expertise.



### **Objective**

The primary objective of this project is to **enhance web application security** by enabling users to identify potential vulnerabilities in their servers quickly and efficiently. Specifically, this tool aims to:

1. **Detect Directory Listing Vulnerabilities**:
   - Identify if directory listing is enabled on a given URL, which could lead to unintended exposure of server files.

2. **Simplify Vulnerability Scanning**:
   - Provide a non-technical interface for users, allowing even those with minimal cybersecurity knowledge to perform basic vulnerability checks.

3. **Educate Users on Web Security**:
   - Raise awareness of the risks associated with directory listing and the importance of securing web server configurations.

4. **Promote Preventative Action**:
   - Equip users with actionable insights that encourage them to review and harden their server configurations.

5. **Provide a Foundation for Expansion**:
   - Serve as a starting point for building more comprehensive vulnerability scanners by adding checks for other common misconfigurations or security flaws.

---

### **How It Aligns with the Objective**

1. **Ease of Use**:
   - The GUI allows users to input a URL and get results with a single click, lowering the barrier to entry for non-experts.
   
2. **Automation**:
   - Automates the process of checking server responses for signs of directory listing, saving time and effort compared to manual checks.

3. **Actionable Feedback**:
   - Displays clear, color-coded results (green for vulnerabilities found, red for none) that inform users of the server's status.

4. **Error Handling**:
   - Ensures smooth operation even when errors like timeouts or invalid inputs occur, making the tool reliable in real-world scenarios.

---

### **Components of the Tool**

1. **Core Functionality**:
   - The `var_vulnerability_scan` function sends an HTTP GET request to the provided URL and checks for signs of directory listing in the server’s response (e.g., the presence of "Index of" in the HTML).

2. **Graphical User Interface (GUI)**:
   - Built using `Tkinter`, the GUI comprises:
     - A text entry field for URL input.
     - A "Scan" button to initiate the check.
     - A result label that provides immediate feedback.

3. **Error Messages**:
   - If no URL is provided or if an invalid URL is entered, the tool prompts the user to correct their input using a dialog box.

---

### **Why is This Important?**

1. **Web Security**:
   - Many servers inadvertently have directory listing enabled, which can expose sensitive data like configuration files, backup files, or logs to attackers. Detecting and disabling this can significantly enhance server security.

2. **User Empowerment**:
   - Non-technical users or small website owners often lack the tools or knowledge to identify such vulnerabilities. This tool empowers them to take a proactive role in securing their websites.

3. **Speed and Simplicity**:
   - Traditional vulnerability scanners are often complex and time-consuming. This tool focuses on one critical vulnerability and provides results in seconds.

---

### **Future Enhancements to Meet Broader Objectives**

1. **Expanded Vulnerability Scanning**:
   - Add checks for other common vulnerabilities, such as:
     - Open ports.
     - Outdated software versions.
     - Misconfigured permissions.

2. **Detailed Reporting**:
   - Generate and export detailed reports in PDF or CSV format to assist users in tracking and addressing vulnerabilities.

3. **Integration with External Tools**:
   - Allow integration with advanced vulnerability scanning frameworks or APIs for a more comprehensive scan.

4. **Customization Options**:
   - Enable users to customize the scan parameters, such as setting timeouts or specifying user-agent strings.

5. **Educational Features**:
   - Add a section that explains the significance of each vulnerability detected and how users can mitigate it.

6. **Cross-Platform Compatibility**:
   - Package the application for seamless use on Windows, macOS, and Linux.

---

### **Glimpes of project**

![image](https://github.com/user-attachments/assets/472bdcbb-03f2-42d8-94ba-6087cc022416)
