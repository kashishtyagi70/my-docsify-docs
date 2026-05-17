# Detection Rules

## Sigma Rule Example

```yaml
title: Suspicious PowerShell Encoded Command

logsource:
  product: windows

detection:
  selection:
    CommandLine|contains:
      - "EncodedCommand"

condition: selection
```

---

## MITRE ATT&CK Mapping

| Technique | ID |
|---|---|
| PowerShell | T1059.001 |