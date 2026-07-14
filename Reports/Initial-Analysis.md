# Initial Phishing Email Analysis

## Email Summary

- Claimed sender: Microsoft Security
- Actual sender domain: `micros0ft-support.example`
- Reply-To domain: `secure-mail.example`
- Subject: Urgent account suspension warning
- Embedded URL: `hxxps://microsoft-security-check[.]example/login`

## Suspicious Indicators

- Brand impersonation
- Typosquatted sender domain using `0` instead of `o`
- Reply-To domain differs from sender domain
- Urgent and threatening language
- Request for immediate account verification
- Suspicious external login link
- Generic greeting

## Initial Risk Rating

**High**

## Initial Assessment

The email displays multiple phishing characteristics, including brand impersonation, domain spoofing, urgency, and a credential-harvesting link.

The message should be treated as malicious in a training context.

## Recommended Actions

- Do not click the link
- Do not reply to the sender
- Report the message to the security team
- Block the sender and related domains
- Search the environment for similar messages
- Reset credentials if the link was accessed