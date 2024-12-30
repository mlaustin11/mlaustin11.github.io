Welcome to my blog
---
One of my hobbies currently is studying for the CRISC (Certified in Risk and Information Systems Control) certification exam.
The CRISC certification is designed for IT professionals, auditors, and risk management professionals who want to demonstrate their expertise in IT risk management and control.
CRISC is a certification that recognizes individuals who have the knowledge and skills to identify and manage IT risk, as well as implement and maintain effective IT controls.

The Four Areas of Focus are:

1. Risk Identification: Identifying and assessing IT risk
2. Risk Assessment: Analyzing and evaluating IT risk
3. Risk Response and Mitigation: Implementing controls to mitigate IT risk
4. Risk and Control Monitoring and Reporting: Monitoring and reporting on IT risk and controls

bash
#!/bin/bash

# Fetch the latest commit message
LATEST_COMMIT=$(git log -1 --format=%s)

# Parse the commit message (e.g., extract the commit hash and author)
COMMIT_HASH=$(git log -1 --format=%H)
AUTHOR=$(git log -1 --format=%an)

# Append the commit message to the README.md file
echo "### Latest Commit: $LATEST_COMMIT" >> README.md
echo "#### Commit Hash: $COMMIT_HASH" >> README.md
echo "#### Author: $AUTHOR" >> README.md
