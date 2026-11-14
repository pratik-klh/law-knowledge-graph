---
type: framework
subject: "[[Civil Procedure]]"
topic:
  - "[[Personal Jurisdiction]]"
aliases:
  - "Steps for Analyzing PJ"
  - "PJ Analysis"
tags:
  - civpro
  - civpro/framework
source: "[[CIVIL PROCEDURE OUTLINE.docx]]"
---

# PJ Analysis Framework

```mermaid
flowchart TD
  Q["Does the court have PJ over D?"] --> S1
  S1["STEP 1: Statutory basis?<br/>Is the forum a state or federal court?"] --> F{"Federal court?"}
  F -- Yes --> FS["Use the PJ statute of the state where it sits"]
  F -- No --> SS["What does the state PJ statute say?<br/>What bases are possible?"]
  FS --> B["Apply facts: Who is D? Where does D live / where incorporated?<br/>What is the c/a? Where did it arise?<br/>What contacts with the forum?"]
  SS --> B
  B --> S2["STEP 2: If basis is specific jurisdiction:<br/>does PJ violate D's due process?<br/>Minimum contacts such that it's fair and reasonable to defend there?"]
  S2 --> SOV["Sovereignty prong: define, then apply facts<br/>(purposeful availment, stream of commerce)"]
  SOV -->|contacts exist| FAIR["Fairness prong: define, then apply facts<br/>(fairness / convenience factors)"]
  SOV -->|no contacts| NO["No PJ: stop"]
```

## Checklist
1. **Notice:** was D properly served? ([[Notice and Service of Process]])
2. **Basis:** do the facts fall within the state [[Long-Arm Statutes|long-arm statute]]?
   - [[General Jurisdiction]]: consent, presence + service ([[Transient Jurisdiction]]), residence/domicile, property, "at home" (systematic and continuous)
   - [[Specific Jurisdiction]]: isolated contact + claim arises from or relates to it
3. **Due process** ([[Due Process Clause]]):
   - **Sovereignty:** [[Minimum Contacts]]. Consider [[Purposeful Availment]], [[Stream of Commerce]], foreseeability ([[World-Wide Volkswagen Corp. v. Woodson]]), and website interactivity ([[Zippo Manufacturing Co. v. Zippo Dot Com]]).
   - **Fairness:** [[Fairness Factors]]
4. **Property-based?** Apply [[Shaffer v. Heitner]].
5. **Waiver:** lack of PJ is waived if not raised in the first Rule 12 response. See [[FRCP Rule 12 - Defenses and Objections]].

> [!tip] Exam
> Argue both sides on contacts and fairness. Pennoyer is **not** good law, so don't apply it on an exam.
