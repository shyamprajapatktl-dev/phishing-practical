# Phishing Attack — Controlled Lab Simulation

## Submitted By

- **Name:** Shyam Kumar
- **Technology Used:** Kali Linux, Social-Engineering Toolkit (SET), Google Chrome, and Gmail

## Project Objective

To understand how phishing attacks work by creating a simulated phishing environment, analysing how users can be deceived by fake login pages and malicious links, and demonstrating how credentials can be captured in a controlled lab environment.
> **Note:** This project was performed as a controlled lab simulation for educational purposes.

## Step 1: Launching Social-Engineering Toolkit (SET)

Social-Engineering Toolkit (SET) was launched in Kali Linux to perform the phishing simulation in a controlled lab environment.

1. Enter the root password.
2. Choose **1 — Social-Engineering Attacks**.
3. Choose **2 — Website Attack Vectors**.
4. Choose **3 — Credential Harvester Attack Method**.
5. Choose **1 — Website Templates**.
6. Enter the IP address shown for the VM.
7. Choose **2 — Google**.

## Step 2: Phishing Login Page

The simulated Google login page was used in the controlled phishing lab. The page demonstrated how users may be tricked into entering their login credentials.

![create login page](/images/Picture1.png)

## Step 3: Capturing Login Activity

The phishing simulation detected submitted login fields and recorded the HTTP request activity in the Kali Linux terminal. This demonstrated how a phishing page can capture user-entered credentials in a controlled lab environment.

![credentials](/images/image.png)

## Step 4: IP Address Conversion

The IP address of the Kali Linux VM was entered into an IP-to-Decimal converter. The IPv4 address was successfully converted into its corresponding decimal representation as part of the lab exercise.
![IP to Decimal](/images/ip.png)

## Step 5: Email Preparation

An email containing recovery-email notification content was prepared for the phishing attack demonstration. The email content was edited as part of the controlled lab exercise.
![email preparation](/images/email.png)
![email preparation](/images/bcc.png)

## Step 6: Creating the Test URL

The converted decimal IP address was combined with the URL format specified in the lab to create a test path. This path was prepared for use in the subsequent controlled phishing demonstration.
![link](/images/link.png)

## Step 7: Sending the Phishing Simulation Email

The prepared email containing the test link was sent to the designated recipient as part of the controlled phishing simulation. This demonstrated how deceptive links can be delivered through email.
![sending email](/images/emailsend.png)
![sending email](/images/emailsen2.png)
![sending email](/images/emailsend3.png)



## Step 8: Captured Login Information

The Social-Engineering Toolkit displayed the login information submitted through the simulated phishing page. This demonstrated how phishing attacks can capture user-entered credentials in a controlled lab environment.

![capture](/images/login.png)

## Conclusion

This lab demonstrated the basic workflow of a phishing attack in a controlled environment, including a simulated login page, email-based delivery, URL preparation, HTTP request monitoring, and credential capture. The exercise highlights the importance of recognising suspicious login pages and deceptive links.

## Technologies Used

- Kali Linux
- Social-Engineering Toolkit (SET)
- Google Chrome
- Gmail
- IP-to-Decimal Converter

## Disclaimer

This project is intended only for authorised, controlled cybersecurity lab environments and educational demonstrations. Do not use phishing pages, deceptive links, or credential-capture techniques against accounts, systems, or people without explicit permission.
