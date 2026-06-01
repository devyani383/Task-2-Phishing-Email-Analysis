# Task-2-Phishing-Email-Analysis

## Objective

Identify phishing characteristics in a suspicious email sample.

## Sample Phishing Email

From: [security-update@paypa1-verification.com](mailto:security-update@paypa1-verification.com)

To: [customer@email.com](mailto:customer@email.com)

Subject: Urgent: Your PayPal Account Will Be Suspended

Dear Customer,

We have detected unusual activity on your PayPal account. To protect your account, we require immediate verification of your account information.

Please click the link below and log in to verify your account:

http://paypal-account-verification-secure.com

Failure to verify your account within 24 hours will result in temporary suspension of your account.

Thank you for your cooperation.

PayPal Security Team

---

## Header Analysis

### Sender Address Analysis

The sender email address is:

[security-update@paypa1-verification.com](mailto:security-update@paypa1-verification.com)

The domain is not an official PayPal domain. The attacker uses "paypa1" instead of "paypal" to deceive users.

### Spoofing Indicator

The sender attempts to impersonate PayPal by using a similar-looking domain name.

### Link Analysis

The provided URL:

http://paypal-account-verification-secure.com

does not belong to the official PayPal website.

---

## Phishing Indicators Found

### 1. Suspicious Sender Address

The sender domain is not an official PayPal domain.

### 2. Email Spoofing

The attacker impersonates a trusted company to gain the victim's trust.

### 3. Urgent Language

The email states that the account will be suspended within 24 hours.

### 4. Threatening Tone

The email uses fear tactics to force immediate action.

### 5. Suspicious Link

The URL directs users to a potentially malicious website.

### 6. Generic Greeting

The email uses "Dear Customer" instead of the recipient's actual name.

### 7. Request for Sensitive Information

The email asks the user to verify account information.

### 8. Social Engineering

The attacker manipulates the user by creating urgency and fear.

### 9. Domain Mismatch

The displayed organization is PayPal, but the sender domain is different.

### 10. Credential Theft Attempt

The likely goal is to steal usernames, passwords, and financial information.

---

## Conclusion

The email contains multiple phishing characteristics including spoofed sender information, suspicious links, urgency tactics, generic greetings, and social engineering techniques.

The email is designed to trick users into revealing sensitive information and should not be trusted.

## Final Verdict

This email is a phishing attempt intended to steal user credentials and financial information by impersonating a trusted organization.





