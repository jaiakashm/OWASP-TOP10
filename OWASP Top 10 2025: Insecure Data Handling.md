# A04: CRYPTOGRAPHIC FAILURES

### Start the machine and visit the site in Task 1, where a key with three known characters is provided. Use Burp Suite to brute-force the remaining character; when the value is 1, the key is valid and reveals the flag.
<br><br>

<img width="637" height="538" alt="image" src="https://github.com/user-attachments/assets/ed29de68-366b-4e85-8582-b6801fba52cb" />

# A05: INJECTION

### In this injection, Server-Side Template Injection (SSTI) is performed. It can be confirmed by entering a Jinja-style expression with a simple mathematical operation; if it gets evaluated, the application is vulnerable to SSTI.
<br><br>
<img width="834" height="225" alt="image" src="https://github.com/user-attachments/assets/d02abd5f-cd03-416b-b0eb-c15ac21392e6" />
### Now, use the `cycler` object in Jinja to read the flag from the system.
<br><br>
<img width="729" height="413" alt="image" src="https://github.com/user-attachments/assets/e396365e-1183-40bf-8898-b91f4e716c49" />

# A08: SOFTWARE AND INTEGRITY FAILURES

### In this step, a malicious payload is crafted to exploit a Python pickle vulnerability; after compiling the code, a Base64-encoded payload is generated, which gets deserialized and reveals the flag.
<br><br>
<img width="827" height="221" alt="image" src="https://github.com/user-attachments/assets/6cf6aa8b-0b8e-425b-8630-639a095ad1e9" />

<img width="721" height="364" alt="image" src="https://github.com/user-attachments/assets/77ec6e93-f086-451a-ae1a-be777f6f95dd" />
