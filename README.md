# Windows-11-Endpoint-Hardening-Baseline
<h1>Step 1: Opening Powershell as Administrator </h1>

<img width="1096" height="292" alt="image" src="https://github.com/user-attachments/assets/7592b399-ed7e-4fdb-9970-c9117c318ec8" />

<h1>Step 2: Capturing the initial security baseline </h1>

<img width="1088" height="462" alt="image" src="https://github.com/user-attachments/assets/8a3883bd-1372-4513-875c-7ba9961fb6b3" />

Im using this script in PowerShell to check my computer's current security settings. This helps me identify security weaknesses before making improvements.

<img width="1195" height="817" alt="image" src="https://github.com/user-attachments/assets/83eebc6d-4910-43e9-b87b-877ed7cee5db" />

This is the report created by my script which is showing that Secure Boot is enabled and my drive is fully encrypted. But some security results are missing, so I need to investigate further to identify potential weaknesses.

<h1>Step 3: Updating Windows Security </h1>

<img width="1292" height="370" alt="image" src="https://github.com/user-attachments/assets/07d1c24f-4b32-4183-8c95-17a799c66665" />

Im checking for Windows updates to keep my computer protected. Here I learn how security patches fix vulnerabilities and help prevent cyberattacks.

<h1>Step 4: Configuring Windows Defender and Firewall</h1>

<img width="1917" height="1005" alt="image" src="https://github.com/user-attachments/assets/87322b31-ea38-480f-ab46-f7904a868226" />

<img width="1917" height="1011" alt="image" src="https://github.com/user-attachments/assets/ccf3c5bc-982a-4836-acd1-285f06daaf17" />

<img width="922" height="498" alt="image" src="https://github.com/user-attachments/assets/f74d6381-1367-4a9f-b5a3-447a2339feb0" />

I checked Windows Defender, Firewall, and ran a virus scan to make sure my computer is protected. I learn how these procedures help protect a device from unauthorized access.

<h1>Step 5: Configuring User Accounts & Least Privilege</h1>

<img width="1318" height="310" alt="image" src="https://github.com/user-attachments/assets/003c6fa9-6bd5-4afd-ad55-a60510bad760" />

I've created a separate local account for administrative tasks. Here I learned how separating accounts is another precaution taken to improve device security.

<img width="682" height="350" alt="image" src="https://github.com/user-attachments/assets/d728f057-3af7-4480-92af-9d26c312cfb3" />

assigning administrator privileges to the local account.

Now since I have a standard and admin account on my local machine I've learned how least privilege is used to prevent certain users from making changes without authorization.

<h1>Step 6: Enabling Windows Device Encryption</h1>

<img width="1328" height="722" alt="image" src="https://github.com/user-attachments/assets/8b661c53-c43c-4560-8476-36812a33c135" />

Here I check whether my computer supports device encryption. With further research I've now learned how encryption protects stored files from unauthorized access.

<img width="435" height="611" alt="image" src="https://github.com/user-attachments/assets/be6da21e-754d-4981-a7c2-959bf4362a62" />

In this step I use PowerShell to check TPM and Secure Boot. I learn how these features help protect encryption keys and the Windows startup process.

<img width="626" height="418" alt="image" src="https://github.com/user-attachments/assets/446dd427-e07c-41d7-8ccf-b3f6647915d7" />

Here I've verified my computer's drive encryption status using PowerShell. 


















