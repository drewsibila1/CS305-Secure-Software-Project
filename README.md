# CS305-Secure-Software-Project
Final project with secure code, checksum, certificate, and testing for Artemis Financial
# Artemis Financial - Secure Software Report

## About the Client
Artemis Financial is a company that helps people plan their finances. They wanted a more secure way to handle their web app’s data transfers, especially for things like saving and retirement plans. I was brought in to secure the communication using encryption and verification.

## My Work
I added SHA-256 hashing for file verification, created a self-signed certificate, and updated the application to use HTTPS instead of HTTP. I verified the checksum output in the console and confirmed secure communication worked in the browser. I also ran OWASP's dependency checker to be sure I didn’t introduce new vulnerabilities.

## What I Learned
Finding and fixing vulnerabilities taught me how important it is to code securely. If software isn’t secure, users and companies can lose trust fast. The OWASP scanner was helpful for catching library issues even outside my own code.

## Security Layers & Testing
I used SHA-256 for hashing, switched the app to HTTPS, and generated certificates with Java Keytool. To check for vulnerabilities, I used OWASP's tool and made sure my code ran without errors after changes.

## Tools I Used
I worked in Eclipse, used Spring Boot, Java Keytool, and Maven for the OWASP dependency check. I’ll use these again in future projects.

## For Employers
This project shows I can follow secure coding practices, refactor safely, and run static tests. It’s a solid example of how I can secure a web app from start to finish.
