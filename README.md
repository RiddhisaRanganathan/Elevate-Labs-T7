# Elevate-Labs-T7

## Method:
- see all the extends that are no longer used or have exceeding permissions.
- Measure the performance of the system using Chrome Task Manager.
- Remove any no longer used extension or remove any exceeding permisiions.
- Measure the performance of the system using Chrome Task Manager.
## How malicious extensions can harm users:

- **Permissions Overreach**: Browser extensions sometimes request more permissions than they actually need. This can grant them access to all tabs, browsing history, and even sensitive user data. If an extension is compromised, it could lead to serious privacy risks.

TO PREVENT: Follow the Principle of Least Privilege (PoLP) and request only the permissions that are absolutely necessary.

- **Data Leakage**: Some extensions unintentionally expose user data by sending browsing activity or personal details to external servers without proper security measures.

TO PREVENT: Always use HTTPS for all communications to prevent data interception.

- **Lack of Content Security Policy (CSP)**: Without a strict CSP, attackers can inject scripts into an extension’s web pages, increasing the risk of cross-site scripting (XSS) attacks.

TO PREVENT: Implement Content Security Policy (CSP) to block inline scripts.

- **Insecure Communication**: Some extensions send sensitive data over unsecured HTTP connections, making it vulnerable to interception by attackers.
TO PREVENT: Always use HTTPS for external communications to prevent data theft.
