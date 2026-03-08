# LibraShield SOC Monitoring

Splunk-based SOC monitoring project detecting brute force login attempts and impossible travel anomalies from simulated authentication logs.

---

## Overview

LibraShield SOC Monitoring simulates a Security Operations Center authentication monitoring environment using Splunk.  

The project demonstrates how security analysts detect suspicious login behavior using log analysis and data visualization.

---

## Security Use Cases

### Brute Force Login Detection
Detects excessive failed authentication attempts by user.

### Impossible Travel Detection
Identifies users logging in from multiple geographic locations within unrealistic timeframes.

### Authentication Event Monitoring
Analyzes authentication activity such as:

- login_success
- login_fail
- password_reset
- account_locked
- vpn_login

---

## SOC Dashboard

![SOC Dashboard](screenshots/LibraShieldDetection)

---

## Detection Examples

### Brute Force Detection

![Brute Force](screenshots/brute_force_detection_results.png)

### Impossible Travel Detection

![Impossible Travel](screenshots/impossible_travel_detection_results.png)

### Investigation Example

![Carlos Investigation](screenshots/carlos_login_investigation.png)

---

## Technology Used

- Splunk Enterprise
- SPL (Search Processing Language)
- Python log generation
- GitHub

---

## Skills Demonstrated

- Security log analysis
- Threat detection engineering
- SOC dashboard development
- Authentication monitoring
- Incident investigation
