## 8. Determine Pass or Fail

Write the algorithm and draw the flowchart for a program that takes a
student's average marks and displays **"Pass"** if average ≥ 50,
otherwise **"Fail"**.

---

**input style:**

### ✔ Pseudocode

```
START
INPUT: avrMark
  IF avrMark > 50
    PRINT: Pass
  ELSE
    PRINT: Fail
  ENDIF
END
```

### ✔ Flowchart

```mermaid
flowchart LR
S((START)) --> IN[/input avrMark/]
IN --> IF{avrMark > 50} -- YES --> OUTP[/Pass/] --> E((END))
IF -- NO --> OUTF[/Fail/] --> E
```

```mermaid
flowchart TD
S((START)) --> IN[/input avrMark/]
IN --> IF{avrMark > 50} -- YES --> OUTP[/Pass/] --> E((END))
IF -- NO --> OUTF[/Fail/] --> E
```
