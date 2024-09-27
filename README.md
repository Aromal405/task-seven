# Taskseven

This repository contains the results of security scans performed on a Metasploitable VM using OpenVAS and Nikto, along with a banner grab using Netcat.

## Contents

- **OpenVAS Report (PDF)**: A comprehensive vulnerability assessment report generated from an OpenVAS scan.
- **Nikto Report (HTML)**: An HTML report detailing vulnerabilities discovered through a Nikto web server scan.
- **Netcat Banner Screenshot**: A screenshot capturing the banner grabbed from a specific service on the Metasploitable VM using Netcat.

## Tools Used

- **OpenVAS**: A free and open-source vulnerability scanner.
- **Nikto**: A web server scanner that tests for various vulnerabilities.
- **Netcat**: A networking utility for reading from and writing to network connections using TCP or UDP.

## Instructions

1. **OpenVAS**:
   - Ensure OpenVAS is installed and running.
   - Target the Metasploitable VM’s IP for the scan.
   - Export the scan report as a PDF.

2. **Nikto**:
   - Install Nikto using your package manager.
   - Run the scan with the command:
     ```bash
     nikto -h http://<Metasploitable_IP> -o nikto_report.html -Format htm
     ```

3. **Netcat**:
   - Use the command to connect to a service:
     ```bash
     nc <Metasploitable_IP> <Port>
     ```
   
