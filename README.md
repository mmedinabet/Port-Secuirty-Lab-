<h1> Port Secuirty lab </h1>
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


![Screenshot 2024-06-11 152435](https://github.com/mmedinabet/Port-Secuirty-Lab-/assets/142737434/be74db0b-f83a-4f26-ae67-a0ef88cd65b7)

I was able to troubleshoot port 10 because I will be using it later. 

<h1> Task 2: Configure Unused Ports to Shutdown</h1>

1. Configure ports not in use to shutdown.
2. Utilize either individual interface login or the range command to achieve this.
   
![Screenshot 2024-06-11 150748](https://github.com/mmedinabet/Port-Secuirty-Lab-/assets/142737434/7884027e-b67e-4992-9f6b-9dfb7557ab82)

<h1> Task 3: Configure Port Security on All Ports </h1>

1. Enable port security on all ports.
2. Implement port-security mac-address sticky to store MAC addresses in memory.
3. Save the configuration using the 'copy run start' command.

![Screenshot 2024-06-11 154801](https://github.com/mmedinabet/Port-Secuirty-Lab-/assets/142737434/0ba83805-8bed-4705-8955-bd658ecc2407)

<h1> Task 4: Test Network Connectivity </h1>

1. Use the ping command to test connectivity between computers.
2. Ensure successful pings among all computers except Laptop-HACKER.

![Screenshot 2024-06-11 155039](https://github.com/mmedinabet/Port-Secuirty-Lab-/assets/142737434/548babc8-29d0-4861-966a-140afb28dcbe)

![Screenshot 2024-06-11 155039](https://github.com/mmedinabet/Port-Secuirty-Lab-/assets/142737434/59224a31-8fb0-4fb3-b901-c1481d67e056)


<h1> Task 5: Review Port Security Configuration </h1>

Review the switchport port-security settings within each interface.

![Screenshot 2024-06-11 155552](https://github.com/mmedinabet/Port-Secuirty-Lab-/assets/142737434/8f486e47-b47e-4d27-a7c7-f55169ac44e1)

![Screenshot 2024-06-11 155619](https://github.com/mmedinabet/Port-Secuirty-Lab-/assets/142737434/82da5699-fb4b-438c-a497-633ebc503c5c)


<h1> Task 6: Test Port Security </h1>

1. Simulate disconnecting PC-1 and connecting Laptop-HACKER to a port.

![Screenshot 2024-06-11 160711](https://github.com/mmedinabet/Port-Secuirty-Lab-/assets/142737434/cf19c7c2-653e-4774-82f6-a523b5a43e70)

![Screenshot 2024-06-11 160837](https://github.com/mmedinabet/Port-Secuirty-Lab-/assets/142737434/55a94e56-d128-4678-a36a-ee9b28f4c0a0)

2. Ensure that the port is disabled due to a security violation.
   
![Screenshot 2024-06-11 161220](https://github.com/mmedinabet/Port-Secuirty-Lab-/assets/142737434/e4a16865-de95-4c2d-b628-581f6f95ff59)

![Screenshot 2024-06-11 162142](https://github.com/mmedinabet/Port-Secuirty-Lab-/assets/142737434/99c4a132-92c6-429b-b264-90cfd5b62bd6)


<h1> Task 7: Check for Security Violations </h1>

1. Verify if any ports are in security violation.
2. Shutdown port in violation and rectify port security settings.
3. Confirm network connectivity and proper functioning of port security measures.

![Screenshot 2024-06-11 4 36 47 PM](https://github.com/mmedinabet/Port-Secuirty-Lab-/assets/142737434/561e064a-9fd3-40e5-a65a-11354c197f6d)

![Screenshot 2024-06-11 4 47 26 PM](https://github.com/mmedinabet/Port-Secuirty-Lab-/assets/142737434/c72ba5d3-40d9-4294-a47d-aaa79c1500cc)

![Screenshot 2024-06-11 4 47 06 PM](https://github.com/mmedinabet/Port-Secuirty-Lab-/assets/142737434/a3768f5c-320d-4a5c-9f9f-ebcc0d5ab5fc)




<h1> Conclusion </h1>

This lab provides hands-on experience in configuring and testing port security measures on a network switch. By completing these tasks, participants gain valuable insights into securing network infrastructure and handling security incidents effectively. Understanding and implementing these practices are essential for maintaining a secure and robust network environment.
