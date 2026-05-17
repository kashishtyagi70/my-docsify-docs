# Incident Response

## Incident Lifecycle

1. Preparation
2. Detection
3. Containment
4. Eradication
5. Recovery
6. Lessons Learned

---

## Example Investigation

### Suspicious PowerShell Execution

Indicators:
- Encoded commands
- External IP communication
- Credential dumping

---

## Investigation Commands

```powershell
Get-Process
Get-Service
Get-WinEvent -LogName Security
```