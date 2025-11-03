# Answers to Part 3

Add your answers to the questions in Part 3, Step 2 below. 

## Vulernability Remediation:Arbitrary Code Execution in PyYAML
### Vulnerability 1: 
1. Which package or library are you addressing?
PyYAML

3. Which CVE is linked to this vulnerability?
CVE-2020-14343

4. What remediation steps do you suggest?
Upgrade the PyYAML package to version 5.4 or later. This addresses a flaw where the library is susceptible to arbitrary code execution when processing untrusted YAML files using the full_load method or the FullLoader

### Vulnerability 2: Denial of Service in Werkzeug
1. Which vulnerability are you addressing?
Werkzeug

3. Which CVE is linked to this vulnerability?
CVE-2023-25577

5. What remediation steps do you suggest? 
Upgrade the Werkzeug package to version 2.2.3 or later. This fixes a Denial of Service (DoS) vulnerability where the multipart form data parser would process an unlimited number of parts, which could lead to unexpectedly high CPU and memory resource usage when an attacker sends crafted multipart data
