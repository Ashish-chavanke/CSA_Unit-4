Cloud Security – Unit 4 Assignment

Launch a Windows Virtual Machine and Connect Using RDP

Student Details

Student Name: Ashish Datta Chavanke

Roll Number: 2124UCSM1017

University: Sanjivani University

Subject: Cloud Security

Unit: 4

Aim

To launch a Windows virtual machine on Amazon EC2, connect to it using Remote Desktop Protocol (RDP), inspect Windows system information, create a local user, verify Windows Firewall, and create a text file or install a basic application.

Tools and Technologies

Amazon Web Services (AWS)

Amazon EC2

Windows Server

Remote Desktop Protocol (RDP)

Windows System Information

Windows Firewall

Practical Steps

1. Launch a Windows EC2 Instance

Open the AWS Management Console, navigate to EC2, and launch a Windows Server instance. Select the required instance type and configure the key pair and network settings.

2. Configure the Security Group

Configure inbound access to allow RDP on TCP port 3389 only from your own public IP address. Do not expose RDP to the entire internet.

3. Connect Using RDP

Obtain the instance's public IPv4 address and Windows administrator credentials through the AWS console. Open Remote Desktop Connection on your computer and connect to the Windows instance.

4. Inspect Windows System Information

After connecting, inspect the Windows desktop and system information, including the operating system and computer details.

5. Create a Local User

Use Windows account-management tools to create a local user with a strong password. Do not include passwords in this repository or in screenshots.

6. Verify Windows Firewall

Open Windows Defender Firewall and inspect its status and configuration. Keep the firewall enabled and verify the relevant settings.

7. Create a Text File or Install an Application

Create a basic text file on the Windows desktop or install a suitable basic application to demonstrate successful use of the virtual machine.

8. Clean Up Resources

After completing the practical and saving the required evidence, stop or terminate the EC2 instance as appropriate to avoid unnecessary charges.

Security Measures

Restricted inbound RDP access to my own public IP address.

Used a strong password for the local user.

Kept Windows Firewall enabled.

Avoided sharing passwords, private keys, and sensitive credentials.

Repository Contents

Unit_4_Cloud_Security_Assignment.pdf — practical report.

screenshots/ — relevant screenshots documenting the practical.

sample.txt — example text file created for the demonstration.

Conclusion

This practical demonstrates how to launch a Windows virtual machine on Amazon EC2, connect securely using RDP, inspect system information, create a local user, verify Windows Firewall, and perform a basic task on the virtual machine.

Note: Screenshots and results should represent the practical actually performed.
