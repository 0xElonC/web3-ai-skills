---
name: solidity-audit
description: Audit Solidity smart contracts and report vulnerabilities
inputs:
  - name: contract_code
    description: Solidity source code
    type: string
outputs:
  - name: report
    description: JSON array of issues
    type: json
---

# Solidity Audit Skill

This skill audits Solidity contracts and reports vulnerabilities.