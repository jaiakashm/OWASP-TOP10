# A01: BROKEN ACCESS CONTROL

### Start the machine
<br><br>
<img width="1335" height="217" alt="image" src="https://github.com/user-attachments/assets/f95b50b8-9fd2-4139-9449-603409a47f2c" />
<br><br>
<img width="1346" height="237" alt="image" src="https://github.com/user-attachments/assets/1d403c83-1bf5-45d6-b90a-242fed949cef" />

### Access the site in Task 3 and modify the ID to 7; due to an IDOR vulnerability, this allows access to other user accounts by altering the URL.
<br><br>
<img width="1055" height="426" alt="image" src="https://github.com/user-attachments/assets/7abb9567-7c80-4535-9833-ba65613e0678" />

### Then, the answers for Task 3 can be obtained from the accessed data.
<br><br>
<img width="1313" height="460" alt="image" src="https://github.com/user-attachments/assets/7e580c23-aa7a-4d9a-9158-07216af8a384" />
<br><br>

# A07: AUTHENTICATION FAILURES

### When attempting to log in as admin, the system indicates that the account already exists; therefore, register a new account as `aDmiN`, which bypasses authentication because the application converts usernames to lowercase, resulting in it being treated as `admin`.
<br><br>
<img width="674" height="695" alt="image" src="https://github.com/user-attachments/assets/f5b40723-e025-40e1-86f8-b580f7807234" />
<br><br>
<img width="649" height="538" alt="image" src="https://github.com/user-attachments/assets/5e4665b6-440e-41ba-b4a6-35d203439618" />

### Therefore, the flag for this task can be obtained from the resulting output.
<br><br>
<img width="840" height="643" alt="image" src="https://github.com/user-attachments/assets/2e3b7bcd-f77e-4074-9d3f-e6dfa5156e0f" />
<br><br>
<img width="1003" height="217" alt="image" src="https://github.com/user-attachments/assets/7ce578c5-3dde-4483-98fc-c43328a89893" />

# A09: LOGGING AND ALERTING FAILURES

### By analyzing the logs, it is possible to identify the IP address attempting the brute-force attack.
<br><br>
<img width="933" height="466" alt="image" src="https://github.com/user-attachments/assets/815d7cb1-84b9-4082-b77f-a996c4581144" />

### Therefore, the identified IP address is obtained from the log analysis.
<br><br>
<img width="853" height="169" alt="image" src="https://github.com/user-attachments/assets/acaa51b1-e421-4f06-8bd0-ba2eb7b0415c" />

### From the brute-force attempt, the attacker was able to successfully log in as admin, which can be confirmed by the response status code.

<br><br>
<img width="935" height="465" alt="image" src="https://github.com/user-attachments/assets/fbd143f6-8c90-4179-9c04-0e22fdf4454f" />
<img width="845" height="223" alt="image" src="https://github.com/user-attachments/assets/6eb8d32b-cafc-4616-a6b6-7451e14c6b5c" />

### After gaining access to the admin account, the attacker accessed an admin-specific resource, which is identified from the logs.
<br><br>

<img width="980" height="484" alt="image" src="https://github.com/user-attachments/assets/9c35df35-c3d7-48ce-9946-128615f6cb48" />
<img width="795" height="188" alt="image" src="https://github.com/user-attachments/assets/dbf7f6e6-0eda-476f-a80c-3bacf548b0d6" />
