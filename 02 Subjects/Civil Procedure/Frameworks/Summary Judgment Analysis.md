---
type: framework
subject: "[[Civil Procedure]]"
topic:
  - "[[Summary Judgment]]"
aliases:
  - "Steps for Analyzing Summary Judgment"
  - "SJ analysis"
tags:
  - civpro
  - civpro/framework
source: "[[CIVIL PROCEDURE OUTLINE.docx]]"
---

# Summary Judgment Analysis

```mermaid
flowchart TD
  A["Who is moving for SJ?"] --> B{"Does the MOVANT bear the<br/>burden of proof at trial?"}
  B -- "Yes (P on own claim; D on affirmative defense)" --> C["Movant must show overwhelming evidence on ALL elements:<br/>no reasonable fact-finder could find otherwise<br/>(admissible evidence)"]
  C --> C2["Burden shifts: non-movant must show remaining questions of fact<br/>(evidence that could be reduced to admissible form;<br/>all inferences in non-movant's favor)"]
  B -- "No (usually D on P's claim)" --> D["Two paths:<br/>(1) Point to ABSENCE of evidence on at least one element (Celotex)<br/>(2) AFFIRMATIVELY DISPROVE at least one element"]
  D --> D2["Burden shifts: non-movant must show the record has evidence<br/>supporting ALL elements, with questions of fact remaining.<br/>Can't rest on mere denials (Celotex)"]
```

## Steps
1. Identify **which party is moving**.
2. Identify **which party has the burden of proof at trial**.
3. **If the movant has the burden at trial** (P on its own claim, or D on an [[Affirmative Defenses|affirmative defense]]):
   - It's not enough to point to gaps in the other side's evidence. The movant must show proof on **all** elements: "Any reasonable fact-finder would have to find for me on each element."
   - This seems to require evidence that would be **admissible at trial**.
   - If shown, the burden shifts to the non-movant to show questions of fact remain. It seems the non-movant can use evidence that **could be reduced to admissible form** at trial, and all inferences are drawn in its favor.
4. **If the movant does NOT have the burden at trial**, it can either:
   - show by **affirmative evidence** that an essential element of the non-movant's case is missing; **or**
   - show the record is **devoid of evidence** on an element. There doesn't need to be a total absence, just so little that no fact-finder could find the element met. **This is usually easier.**
   - Then the non-movant must show the record has evidence supporting **all** elements and that questions of fact remain. It **cannot rest on mere denials** ([[Celotex Corp. v. Catrett]]).

See [[Summary Judgment]] · [[Burden of Production and Persuasion]] · [[Genuine Dispute of Material Fact]]
