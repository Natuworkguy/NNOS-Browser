# Security Policy

## Supported Versions

The NNOS Browser project is for demonstration purposes and is not a fully functional or secure browser.
As such, it is **not recommended for production use**. Security updates are not guaranteed. Below are the supported versions:

| Version   | Supported          |
|-----------|--------------------|
| 1.0       | ❌ Not Supported   |
| 2.0       | ✅ Supported       |

## Reporting a Vulnerability

If you discover a security vulnerability in this project, please report it to help us improve the project.
To report a vulnerability, email info@nathannetwork.com

## Known Limitations

- **Iframe Security**: The project uses an `iframe` for displaying content, which is vulnerable to certain attacks (e.g., XSS, clickjacking).
- **Protocol Enforcement**: Input URLs without protocols default to `http://` or `https://`, which may lead to insecure connections.
- **LocalStorage**: Data persistence relies on `localStorage`, which is not secure for sensitive data.

## Recommendations for Users

- **Do not use for sensitive activities**: This project is for educational or experimental use only.
- **Inspect third-party content**: Be cautious when using the iframe to load external URLs.
- **Avoid storing sensitive data**: LocalStorage is not secure for sensitive information.

## Security Best Practices for Developers

If you plan to extend or modify this project:
1. **Use HTTPS by Default**: Enforce HTTPS connections to avoid insecure protocols.
2. **Sanitize User Input**: Validate and sanitize all user inputs to prevent XSS and other injection attacks.
3. **Implement CSP**: Use a Content Security Policy to mitigate the impact of potential XSS attacks.
4. **Avoid Privileged API Access**: Do not extend the project to access privileged system resources without proper safeguards.

## Acknowledgments

We appreciate the security community's efforts to identify and responsibly disclose vulnerabilities. Thank you for helping us improve this project!
