# CODTECH-Task3
Name: Karthiyayini.S

Company: CODETECH IT SOLUTIONS

ID: CT8CSEH1437

Domain: Cybersecurity&Ethical hacking

Duration:8 weeks

Mentor:

Title: VULNERABILITY SCANNING TOOL

Objective: 

•	Creating a demonstration of security vulnerabilities like SQL injection, XSS, and insecure authentication directly in HTML and CSS is challenging because these vulnerabilities typically involve server-side processing and dynamic interactions. 

•	However, we can simulate certain aspects using HTML forms and JavaScript to showcase potential risks.


1.	XSS Vulnerability:
   
o	The form (xssForm) allows users to input a search query (searchQuery).

o	When submitted, the JavaScript code directly inserts the input into the searchResultsDiv without proper validation or encoding. This simulates an XSS vulnerability where an attacker could inject malicious scripts.


2.	Insecure Authentication Mechanism:

o	The form (loginForm) allows users to input a username (username) and password (password).


o	The JavaScript code checks the input values (username and password) and simulates authentication based on hardcoded credentials (admin and admin123). This simulates an insecure authentication mechanism without server-side verification.


Output:

When you open this HTML file in a browser and interact with it:


•	XSS Vulnerability: If you enter <script>alert('XSS');</script> into the search field and submit, it will directly execute the JavaScript code within the context of the page, showing an alert box.


•	Insecure Authentication: If you enter admin as the username and admin123 as the password and submit the form, it will simulate a successful login as an administrator.





•	Limitations: This example only simulates basic aspects of XSS and insecure authentication for educational purposes. Real-world exploitation and detection often require more sophisticated tools and techniques.


•	Security: Always exercise caution when demonstrating or testing vulnerabilities, even in controlled environments. Ensure you have appropriate permissions and follow ethical guidelines.


OUTPUT:

![Screenshot 2024-07-07 191402](https://github.com/Karthiyayini11/CODTECH-Task2/assets/98526194/93d60b3c-4061-496e-a32b-1ce3dbb5601b)



