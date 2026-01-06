# ShopSwift – Secure Static Website on AWS

This project demonstrates how to host a **secure static website** on AWS using modern cloud best practices.

The focus of this project is **frontend infrastructure and security**, not backend application logic.

---

## Architecture Overview

Users access the website via Amazon CloudFront.  
Traffic is protected by AWS WAF and encrypted using HTTPS with AWS Certificate Manager.  
Static website files are stored in Amazon S3.  
DNS routing is handled by Amazon Route 53.

---

## AWS Services Used

- Amazon S3 – Static website hosting
- Amazon CloudFront – Global CDN
- Amazon Route 53 – DNS management
- AWS Certificate Manager (ACM) – SSL/TLS certificates
- AWS WAF – Web Application Firewall

---

## Security Features

- HTTPS enforced using ACM
- AWS WAF protecting against common web attacks
- Private S3 bucket accessed only via CloudFront
- Origin Access Control (OAC) enabled

---

## Skills Demonstrated

- Static website hosting on AWS
- CDN configuration
- DNS configuration
- SSL certificate deployment
- Web security using AWS WAF
- Cloud monitoring and traffic analysis

---

## Notes

- This project focuses on **frontend infrastructure only**
- Backend services will be designed separately
- Infrastructure was created manually via the AWS Console for learning purposes

---

## Author

Akunna  
AWS Cloud Project – Static Website Hosting

