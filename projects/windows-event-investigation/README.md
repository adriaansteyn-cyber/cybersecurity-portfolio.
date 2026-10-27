# Windows Event Log Investigation

## Project Overview

This project focuses on the fundamentals of Windows security event analysis and digital forensic investigation. The objective is to understand how Windows records security-related activity and how event logs can support the identification and investigation of suspicious behaviour.

## Investigation Objectives

- Understand the role of Windows Security event logs in incident investigations.
- Identify relevant event IDs and interpret the information they contain.
- Examine authentication-related events, including failed logon attempts.
- Practise documenting evidence, observations, and investigation findings.
- Develop foundational skills relevant to Security Operations (SOC) and Digital Forensics and Incident Response (DFIR).

## Investigation Scope

The investigation focuses on Windows security events, particularly authentication activity and indicators that may warrant further examination.

Relevant event IDs include:

- **4624** — A user account successfully logged on.
- **4625** — An account failed to log on.
- **4634** — An account was logged off.
- **4648** — A logon was attempted using explicit credentials.

These events must be interpreted in context. A single event does not automatically establish malicious activity.

## Methodology

The investigation process is intended to follow these steps:

1. Identify the relevant Windows event logs.
2. Review event IDs, timestamps, account details, and logon information.
3. Establish the sequence of events where possible.
4. Look for patterns that may warrant further investigation.
5. Document observations and distinguish confirmed facts from hypotheses.
6. Record limitations and recommend any appropriate follow-up checks.

## Findings

Investigation findings will be documented here after the relevant event records have been examined and verified.

No conclusions about malicious activity should be drawn without supporting evidence.

## Skills Developed

- Windows Security event log interpretation.
- Authentication-event analysis.
- Evidence-based investigation and documentation.
- Incident investigation methodology.
- Technical reporting and analytical reasoning.

## Project Status

**Status:** Documentation and practical development in progress.

Further details, supporting evidence, and verified findings will be added as the investigation develops.

---

*This project is intended for educational purposes and practical cybersecurity skills development.*
