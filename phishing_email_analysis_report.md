 ## Phishing Email Analysis Report

## Objective
Identify phishing characteristics in a suspicious email sample and summarize the findings to improve awareness of phishing tactics and email threat analysis skills.

---

## Sample Phishing Email
```
From: "PayPal Support" <support@paypa1.com>
To: user@example.com
Subject: Urgent: Account Access Limited

Dear Customer,

We have noticed suspicious activity in your PayPal account. For your protection, your account access has been temporarily limited.

Please confirm your identity by clicking the link below:

https://paypal-security-alert.com/verify

If you do not respond within 48 hours, your account will be permanently suspended.

Thank you for your prompt attention to this matter.

Sincerely,
PayPal Security Team

Attachment: Account_Verification_Form.zip
```

---

## Phishing Indicators Found

1. **Sender's Email Address**:  
   - Appears as "support@paypa1.com" (note the use of "1" instead of "l" in "paypal").
   - Does not match the official PayPal domain.

2. **Email Header Discrepancies**:  
   - (In a real scenario, use an online header analyzer. Here, the sender domain is already suspicious.)

3. **Suspicious Links**:  
   - The link points to `https://paypal-security-alert.com/verify`, which is not an official PayPal domain.

4. **Urgent/Threatening Language**:  
   - Phrases like "your account access has been temporarily limited" and "permanently suspended" create a sense of urgency and fear.

5. **Mismatched URLs**:  
   - The displayed link is not the real PayPal website.

6. **Spelling/Grammar Errors**:  
   - The email is generally well-written, but the generic greeting ("Dear Customer") is a red flag.

7. **Unusual Attachments**:  
   - The attachment "Account_Verification_Form.zip" is suspicious and could contain malware.

---

## Summary of Phishing Traits
- Spoofed sender address (paypa1.com instead of paypal.com)
- Urgent and threatening language
- Suspicious/mismatched links
- Generic greeting
- Suspicious attachment

---

## Key Concepts
- **Phishing**: Fraudulent attempt to obtain sensitive information by disguising as a trustworthy entity.
- **Email Spoofing**: Forging the sender's address to appear as a legitimate source.
- **Header Analysis**: Examining technical details in email headers to spot inconsistencies.
- **Social Engineering**: Manipulating people into divulging confidential information.


---

## How to Run This Task Yourself

1. Obtain a sample phishing email (search for examples online).
2. Analyze the sender's address, email headers, links, and content.
3. Use an online header analyzer (e.g., MXToolbox).
4. List and summarize all phishing indicators found.

---

## References
- [Phishing.org](https://www.phishing.org/)
- [MXToolbox Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- [Google Admin Toolbox](https://toolbox.googleapps.com/apps/messageheader/)

---

**This repository contains my phishing email analysis and findings for the Cyber Security Internship Task 2.** 
