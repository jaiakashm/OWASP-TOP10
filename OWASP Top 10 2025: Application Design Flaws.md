# A02: SECURITY MISCONFIGURATIONS

### Start the machine
<br><br>
<img width="1261" height="122" alt="image" src="https://github.com/user-attachments/assets/9ccc2625-f4c9-457a-a555-f5e0a3d2b2cd" />
<br><br>
<img width="955" height="297" alt="image" src="https://github.com/user-attachments/assets/cf1446b6-3961-4f8f-a24e-8e87f2f644ad" />
<br><br>
### From the homepage, it is observed that the application accepts only numeric values for the user ID; entering alphabetic input results in an error or invalid response.
<br><br>
<img width="1235" height="189" alt="image" src="https://github.com/user-attachments/assets/62a2d5d3-da9b-419c-9a09-fd904ac3100b" />
<br><br>
<img width="1264" height="108" alt="image" src="https://github.com/user-attachments/assets/d018f917-5cd7-4c26-a3f2-9066c6ac2b13" />
<br><br>
# A03: SOFTWARE SUPPLY CHAIN FAILURE
<br><br>
<img width="914" height="399" alt="image" src="https://github.com/user-attachments/assets/6f0e8506-872f-437b-bef0-745c0873fe21" />

### Navigate to the `api/health` endpoint to check the application's status.
<br><br>
<img width="1133" height="273" alt="image" src="https://github.com/user-attachments/assets/9e9bc560-e5f6-4942-ada9-62886c16fb14" />

### Next, navigate to the `api/process` endpoint and change the request method from GET to POST as specified in the task file.
<br><br>
<img width="1071" height="642" alt="image" src="https://github.com/user-attachments/assets/ce522bab-b354-47b8-8478-39022aefe41f" />
<br><br>
<img width="1279" height="249" alt="image" src="https://github.com/user-attachments/assets/02716ad4-cf43-4c1b-868d-d101e9c680f9" />

### Add the `Content-Type` header as `application/json`, then include the JSON payload in the request to retrieve the flag.
<br><br>
<img width="1256" height="388" alt="image" src="https://github.com/user-attachments/assets/3c73739b-2cbb-4040-898a-ced762d8d87e" />
<br><br>
<img width="1266" height="111" alt="image" src="https://github.com/user-attachments/assets/340b32ed-5cad-4c88-af2f-192758064791" />
<br><br>
# A04: CRYPTOGRAPHIC FAILURES

### When we see the site source code we can able to see the decrytion key click on that to see the key
<br><br>
<img width="1255" height="300" alt="image" src="https://github.com/user-attachments/assets/9b6757d9-30d4-46a1-a9d6-e537c81703f7" />
<br><br>
<img width="639" height="241" alt="image" src="https://github.com/user-attachments/assets/8bb7f38c-4bbd-4417-a310-7319d2f9da1b" />

### Use any online AES decryption tool to decrypt the encrypted data.
<br><br>
<img width="868" height="377" alt="image" src="https://github.com/user-attachments/assets/81cfb6b9-9401-4776-ae84-118bea4e80b8" />
<br><br>
<img width="1262" height="103" alt="image" src="https://github.com/user-attachments/assets/ac377b17-7cb1-479f-919d-a798e739d8dd" />
<br><br>
# A06: INSECURE DESIGN

### The application has an insecure design, allowing access to the `api/users` endpoint to view user data.
<br><br>
<img width="584" height="379" alt="image" src="https://github.com/user-attachments/assets/1d970cd1-7853-41fa-9d83-66dd3fa7fe75" />

### Since there are three users, navigate to the `api/messages/admin` endpoint to view the messages associated with the admin user.
<br><br>
<img width="907" height="260" alt="image" src="https://github.com/user-attachments/assets/acaa33b2-722f-4c87-858a-805d55ed91b9" />
<br><br>
<img width="1363" height="116" alt="image" src="https://github.com/user-attachments/assets/c6aae7c7-afcb-4611-8a92-58dd31987f2b" />
