# Hashcat MD5 Password Cracking Lab

**Date:** 19/08/2026  
**Type:** Cyber Security Practical Report

## Submitted By
**Name:** Shyam Kumar

## Technology Used
- Hashcat
- MD5 Hashing
- Windows CMD
- Password Security Analysis

## Project Objective
The objective of this project is to understand MD5 hashing and password security and to demonstrate how Hashcat can be used to recover a password from an MD5 hash in a controlled lab environment.

The project also aims to analyze the strength of a password and understand the importance of using strong passwords and secure hashing algorithms.

## Lab Procedure

### 1. MD5 Hash Generation
The first six characters of the name were converted into an MD5 hash value using an online MD5 hash generator.

![MD5 hash](MD5.png)

### 2. Saving MD5 Hash in `hash.txt`
The generated MD5 hash value was copied and saved in the `hash.txt` file for Hashcat analysis.
![savingmd5](savingMD5.png)

### 3. Password Security Check
The selected password was tested using an online password security checker to evaluate its security strength.
![password](pass.png)


### 4. Hashcat Password Recovery
Hashcat was used to analyse the MD5 hash using the specified command. After the process was completed, the recovered password was verified from the `cracked.txt` file.
![password recovery](recovery.png)

## Conclusion
This lab demonstrated the use of MD5 hashing and Hashcat for password security analysis in a controlled environment. It also highlighted the importance of using strong passwords and secure hashing algorithms.

## Disclaimer
This practical should only be performed in an authorized lab environment and on hashes for which you have permission to conduct security testing.
