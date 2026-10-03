# Phishing Email Analysis

## Objective

The objective of this task was to identify phishing characteristics in a suspicious email sample.

## Sample Email

**From:** Microsoft Account Security <security-alert@micros0ft-support.example>

**Subject:** URGENT: Your Microsoft Account Will Be Suspended!

**Message:** The email claims that unusual login activity was detected and asks the recipient to verify the account within 24 hours.

## Phishing Indicators Found

### 1. Suspicious Sender

The sender address is:

`security-alert@micros0ft-support.example`

It does not appear to be an official Microsoft email address.

### 2. Urgent Subject

The subject uses words such as **"URGENT"** and threatens account suspension.

This creates pressure and encourages the recipient to act quickly without verifying the message.

### 3. Suspicious URL

The email contains:

`https://micros0ft-support.example/verify`

The domain is suspicious and is not an official Microsoft domain.

It also uses the number **0** instead of the letter **o** in `micros0ft`.

### 4. Suspicious Request

The recipient is asked to click a verification link.

Such links could potentially be used to collect credentials or other sensitive information.

### 5. Fear and Urgency

The email says the account will be suspended within 24 hours.

This is a social-engineering technique designed to make the recipient act quickly.

### 6. Generic Language

The email begins with **"Dear Customer"** instead of using a specific recipient name.

The wording also does not appear consistent with a normal official security notification.

## Conclusion

The email contains multiple phishing indicators, including a suspicious sender address, urgent language, a suspicious domain, a misleading domain name, and a request to verify the account through a link.

The safest response would be to avoid clicking the link and independently verify the account through the organization's official website or application.
