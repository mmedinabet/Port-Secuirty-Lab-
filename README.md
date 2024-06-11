<h1> Port Secuirty lab </h1>
Introduction:

In this port secuirty lab, we will delve into configuring and testing port security on a network switch using Packet Tracer simulation software. The lab is structured into tasks designed to review, configure, and test port security measures to enhance network integrity and mitigate unauthorized access. By following these steps, participants will gain practical experience in securing network ports and handling security violations effectively.

![Screenshot 2024-06-11 144924](https://github.com/mmedinabet/Port-Secuirty-Lab-/assets/142737434/8df16143-313a-49fb-938e-bbec2e3a09db)


![Screenshot 2024-06-11 151257](https://github.com/mmedinabet/Port-Secuirty-Lab-/assets/142737434/2aa3a907-66f0-440e-8265-e5c1f70c6c8f)

<h1> Task 1: Review and Verify Switch Configuration</h1>

1. Log in to the switch and enter enable mode.
2. Use the 'show run' command to review the configurations.
   
![Screenshot 2024-06-11 144828](https://github.com/mmedinabet/Port-Secuirty-Lab-/assets/142737434/f4b6e670-54bb-4ce1-89d5-3c3ef8562997)

3. Identify and ensure unused ports are shutdown.
4. Confirm that ports in use are set to 'no shutdown'.

![Screenshot 2024-06-11 145041](https://github.com/mmedinabet/Port-Secuirty-Lab-/assets/142737434/defb7c92-30b5-4c29-94fa-5b29effca5a6)

5. Verify that all ports are configured with port security.
   
![Screenshot 2024-06-11 150748](https://github.com/mmedinabet/Port-Secuirty-Lab-/assets/142737434/7884027e-b67e-4992-9f6b-9dfb7557ab82)

<h1> Task 2: Configure Unused Ports to Shutdown</h1>

Configure ports not in use to shutdown.
Utilize either individual interface login or the range command to achieve this.

<h1> Task 3: Configure Port Security on All Ports </h1>

Enable port security on all ports.
Implement port-security mac-address sticky to store MAC addresses in memory.
Save the configuration using the 'copy run start' command.

<h1> Task 4: Test Network Connectivity </h1>

Use the ping command to test connectivity between computers.
Ensure successful pings among all computers except Laptop-HACKER.

<h1> Task 5: Review Port Security Configuration </h1>

Review the switchport port-security settings within each interface.

<h1> Task 6: Test Port Security </h1>

Simulate disconnecting PC-1 and connecting Laptop-HACKER to a port.
Ensure that the port is disabled due to a security violation.

<h1> Task 7: Check for Security Violations </h1>

Verify if any ports are in security violation.
Shutdown port in violation and rectify port security settings.
Confirm network connectivity and proper functioning of port security measures.

<h1> Conclusion </h1>

This lab provides hands-on experience in configuring and testing port security measures on a network switch. By completing these tasks, participants gain valuable insights into securing network infrastructure and handling security incidents effectively. Understanding and implementing these practices are essential for maintaining a secure and robust network environment.
