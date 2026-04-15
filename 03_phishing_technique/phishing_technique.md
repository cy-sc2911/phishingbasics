Phishing campaigns use technical manipulation to deceive targets and bypass defences. Here are some of the most common techniques attackers use to trick victims into interacting with malicious content.

## URL and Domain Manipulation
As a pentester, one of our primary goals is to get our target to click on a URL we control. To achieve this, we can use some of the technique below:
- **URL Masking**: Involves disguising a malicious IRL behind a legitimate-looking hyperlink. For example, an attacker might display *https://tryhackme.com* while redirecting users to *http://phisher.thm*.
- **Homograph Attacks**: Exploit visual similarities between domain name characters, for example, replacing "o" with "0" or using Cyrilic characters. An attacker might register a domain like 'goo0gle.com' that looks identical to the legitimate one but redirects users to a malicious site.
- **Typosquatting**: Involves registering domains similar to legitimate ones, relying on users making typing errors, for example, *tryhacme.com* instead of *tryhackme.com*. As a pentester, we can use these domains for phishing websites or malware delivery.

Attackers can use URL shorteners to hide a link's true destination. These URLs are more complicated for users to inspect and can bypass basic security checks.

## Email Spoofing Fundamentals
Email spoofing is a technique for impersonating a legitimate sender by modifying email headers. For example, we can spoof the "From" field to display a trusted sender's email address, like a manager or someone from HR. If a domain is lacking security measures for authentication, an attacker can use a Python script to modify their email address. This is possible because **SMTP (Simple Mail Transfer Protocol)** does not have built-in functionality for authenticating email addresses.


