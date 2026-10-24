# govt-scam
about detectinging fake links
Government Scam Detection Module
Enter URL here
 Check
{% if result %}
Result: {{ result }}
{% for reason in reasons %}
{{ reason }}
{% endfor %}
Phishing Awareness Tips:
Always check for .gov.in domains
Do not click suspicious SMS links
Verify government schemes from official portals
{% endif %}
Develop a platform to detect fake government links, messages, and schemes.
Provide one portal for authenticity verification.
Generate trust score for user safety.
Solution Description

User enters URL / message / scheme name.
System checks domain (.gov.in), SSL, and domain age.
AI scans scam keywords (KYC, subsidy, urgent).
Matches with govt database.
Shows result: Safe / Suspicious / Scam.
Prototype
Web-based application.
Modules: URL Checker, Message Scanner, Scheme Verifier.
Displays trust score and risk alerts.

Innovation & Uniqueness
Govt-specific scam detection system.
Combines AI + URL analysis + database verification.
Simple interface for rural & non-technical users.
Awareness + detection in one platform.
<img width="1783" height="1218" alt="image" src="https://github.com/user-attachments/assets/35183416-bb40-4b44-b226-0adb42906fac" />
