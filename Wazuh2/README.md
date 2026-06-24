Threat Detection: A Wazuh SIEM agent monitors the endpoint and detects critical security events (like brute-force logon failures).
Cloud Automation: The event telemetry is instantly formatted and shipped over the network to an n8n cloud webhook trigger.
Data Parsing: An n8n expressions engine isolates the nested JSON payload parameters (like Rule ID, description, and the target host machine).
AI Triage: The structured parameters are sent to Google Gemini, which acts as a virtual assistant—instantly evaluating the severity, analyzing the context, and generating a structured incident report complete with remediation steps.
