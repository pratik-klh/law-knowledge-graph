---
type: framework
subject: "[[Civil Procedure]]"
topic:
  - "[[Erie Doctrine]]"
aliases:
  - "Erie Test"
  - "Erie analysis"
tags:
  - civpro
  - civpro/framework
source: "[[CIVIL PROCEDURE OUTLINE.docx]]"
---

# Erie Analysis Framework

## The basic Erie test
```mermaid
flowchart TD
  E["Erie Test"] --> F{"Federal issue?<br/>(e.g., interpreting a federal statute)"}
  F -- Yes --> F1["Substance: federal law"]
  F -- Yes --> F2["Procedure: federal law"]
  F -- No --> S1["Substance: STATE law<br/>(e.g., negligence)"]
  F -- No --> S2["Procedure: FEDERAL law<br/>(e.g., # of days to answer)"]
```

## Full decision tree for a state-law claim in federal court
```mermaid
flowchart TD
  A{"What federal source conflicts<br/>with the state law?"} -- "Federal statute" --> ST{"Does the statute cover the issue?<br/>(read broadly: Stewart)"}
  ST -- Yes --> STV["Valid exercise of Congress's power?<br/>Yes: statute wins (Supremacy Clause)"]
  ST -- No --> BY
  A -- "FRCP" --> R{"Direct collision? Is a legitimate<br/>FRCP directly on point? (read narrowly: Walker)"}
  R -- Yes --> RW["FRCP wins (Hanna)"]
  R -- No --> BY
  A -- "Judge-made practice" --> BY["Byrd balancing:<br/>state interest vs federal interest<br/>+ likely outcome determinative?"]
  BY --> OUT{"Substantive or procedural?"}
  OUT -- Substantive --> SL["Apply state law,<br/>using forum state's choice-of-law rules (Klaxon)"]
  OUT -- Procedural --> FL["Apply federal law"]
```

## Checklist
1. Is jurisdiction based on **FQ**? If so, apply federal law and stop.
2. **Diversity or supplemental** over a state claim? Identify the conflict.
3. Federal **statute** on point? See [[Stewart Organization v. Ricoh Corp.]] (broad reading, statute wins if valid).
4. **FRCP** on point with a direct collision? See [[Hanna v. Plumer]] and [[Walker v. Armco Steel Corp.]]
5. Otherwise use the [[Byrd Balancing Test]] (with the [[Outcome Determinative Test]] from [[Guaranty Trust Co. v. York]]).
6. If state law applies, **which state?** Use the forum state's conflict rules ([[Klaxon Co. v. Stentor Electric Manufacturing]]). After a §1404 transfer, use the transferor's law; after §1406, the transferee's ([[Transfer of Venue]]).
