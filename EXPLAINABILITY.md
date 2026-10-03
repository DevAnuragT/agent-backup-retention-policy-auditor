# Decision and Reasoning

Compare backup sets with declared retention, encryption, and restore evidence. The implementation evaluates each field rule independently. Overall status follows the number of passed checks; failures include observed evidence and a correction action.

# Inputs and Data Sources

Input is caller-provided JSON. Rule definitions live in metadata.json. No web, credentials, or external service are consulted.

# Known Limitations

Checks validate submitted representation only. They cannot confirm real-world truth, legal sufficiency, or safety. Human review remains required.
