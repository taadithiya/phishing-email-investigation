\# MITRE ATT\&CK Mapping



\## T1566.002 — Phishing: Spearphishing Link



The simulated email contains a link intended to direct the recipient to a fake account-verification page.



Observed evidence:



\- Suspicious verification URL

\- Microsoft 365 impersonation

\- Urgent account-suspension warning

\- Request for immediate user action



\## T1204.001 — User Execution: Malicious Link



The scenario depends on the recipient clicking the embedded link.



Observed evidence:



\- Direct instruction to verify the account

\- Link presented as the required action

\- Urgency designed to encourage immediate clicking



\## Mapping Summary



| Technique ID | Technique | Evidence |

|---|---|---|

| T1566.002 | Spearphishing Link | Phishing email containing a suspicious account-verification URL |

| T1204.001 | Malicious Link | User is encouraged to click the embedded link |



\## Scope Note



This project uses a simulated and defanged phishing email. No live malicious URL, payload, or credential-harvesting page was used.

