# Web Security Assessment Script
This Python script assesses the security posture of a web application by checking for security headers, potential SQL injection vulnerabilities, and open redirect vulnerabilities.

# Features
Security Headers Check: Verifies the presence of Content-Security-Policy, X-Content-Type-Options, X-Frame-Options, and X-XSS-Protection headers.
SQL Injection Test: Checks for potential SQL injection vulnerabilities by appending a single quote to the URL.
Open Redirect Check: Tests for potential open redirect vulnerabilities by attempting to redirect to a malicious URL.
# Usage
Input: Run the script and enter the URL of the web application when prompted.

Output: The script will display the security headers and indicate whether potential vulnerabilities were detected.
# Requirements
Python 3.x

requests library (install via pip install requests)
