---
type: framework
subject: "[[Civil Procedure]]"
topic:
  - "[[Subject Matter Jurisdiction]]"
aliases:
  - "Analyzing Supplemental Jurisdiction"
tags:
  - civpro
  - civpro/framework
source: "[[CIVIL PROCEDURE OUTLINE.docx]]"
---

# Supplemental Jurisdiction Analysis

```mermaid
flowchart TD
  A{"Multiple claims or<br/>multiple parties?"} -- "No (1 P, 1 D, 1 claim)" --> X["No supplemental jdx needed"]
  A -- Yes --> B{"Does the extra claim/party have<br/>independent SMJ?"}
  B -- Yes --> Y["No need for supplemental jdx"]
  B -- No --> C{"Same case or controversy?<br/>(common nucleus of operative fact)"}
  C -- No --> Z["No supplemental jdx"]
  C -- Yes --> D{"Original claim based on<br/>FQ or diversity?"}
  D -- Diversity --> E{"Does joining the new party<br/>destroy diversity? (§1367(b))"}
  E -- Yes --> Z
  E -- No --> F["Apply §1367(c) discretionary factors"]
  D -- "Federal question" --> F
```

## Steps
1. Are there **multiple claims or parties**? If 1 P, 1 D, 1 claim, there's nothing to analyze.
2. Does the extra claim or party have **independent SMJ** ([[Diversity Jurisdiction]] or [[Federal Question Jurisdiction]])? If so, stop.
3. Is it part of the **same case or controversy** ([[Common Nucleus of Operative Fact]])? If not, there's no supplemental jurisdiction.
4. Is the original claim based on **FQ or diversity**?
5. If **diversity**: will joining the new party destroy diversity (§1367(b))?
6. Apply the **§1367(c)** factors: novel or complex state issue · state claim predominates · original claims dismissed · exceptional circumstances.

See [[Supplemental Jurisdiction]] · [[28 USC 1367 - Supplemental Jurisdiction]]
