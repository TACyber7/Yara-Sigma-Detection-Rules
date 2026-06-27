# YARA & Sigma Detection Rules

A public repository containing YARA and Sigma detection rules created for malware detection, threat hunting, and detection engineering practice.

## About

This repository documents detection content that I have developed and tested in my personal Detection Engineering lab. The goal is to demonstrate practical detection engineering skills through high-quality, well-tested detection rules.

The rules are designed to detect adversary techniques observed in real-world environments while minimizing false positives whenever possible.

## Repository Contents

- Sigma detection rules
- YARA malware detection rules
- MITRE ATT&CK mappings
- Documentation for each detection

## Lab Environment

Rules are validated in a lab environment using technologies such as:

- Windows Event Logs
- Sysmon
- Elastic Stack (ELK)
- Atomic Red Team
- Chainsaw

## Testing Methodology

Each rule is developed using a repeatable workflow:

1. Select a MITRE ATT&CK technique
2. Generate telemetry using Atomic Red Team or custom simulations
3. Collect logs
4. Develop the detection
5. Validate against generated telemetry
6. Tune to reduce false positives
7. Document the rule

## Goals

This repository serves as my public detection engineering portfolio and demonstrates:

- Detection engineering
- Threat detection
- Threat hunting
- Sigma rule development
- YARA rule development
- Detection testing and validation

## Disclaimer

These rules are provided for research and educational purposes. They should be tested within your own environment before production deployment.

