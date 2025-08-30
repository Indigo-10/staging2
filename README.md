# Staging2

Custom malware staging repository for an upcoming internal red team vs blue team competition. Contains compiled tools and payloads ready for deployment during simulated attack scenarios.

## Contents

- **credStealer.dll** - Credential harvesting payload
- **Inject-x64.exe** - 64-bit process injection utility  
- **PsExec64.exe** - Lateral movement tool for remote execution

## Usage

```cmd
# Process injection example
Inject-x64.exe credStealer.dll lsass.exe

# Privilege escalation
runas /user:target cmd
```

## Purpose

This staging area contains pre-compiled offensive tools customized for specific competition scenarios. The tools are designed to simulate real-world attack techniques while operating within the controlled environment of internal security exercises.

## Competition Context

Developed for internal red vs blue team exercises where red team operators test defensive capabilities in a controlled environment. These tools help evaluate incident response procedures, detection capabilities, and defensive countermeasures.

---
*For authorized internal security competitions and training exercises only*
