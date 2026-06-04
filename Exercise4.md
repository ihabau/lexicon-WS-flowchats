## 4. Positive, Negative, or Zero Check

Write the algorithm and flowchart to input a number and display whether
it is positive, negative, or zero.

---

### ✔ Pseudocode

```
START
  INPUT: number
  IF number < 0
    PRINT: negative
  ELSEIF: number > 0
    PRINT: positive
  ELSE
PRINT: zero
  ENDIF
END
```

### ✔ Flowchart

```mermaid
flowchart LR
S((START)) --> IN[/input: number/]
IN --> IF1{IF: number < 0} -- YES --> OUTN[PRINT: negative number.] --> E((END))
IF1 -- NO --> IF2{IF number > 0} -- YES --> OUTP[PRINT: positive number.] --> E
IF2 -- NO --> OUT0[PRINT: number zero.] --> E
```

```mermaid
flowchart TD
S((START)) --> IN[/input: number/]
IN --> IF1{IF: number < 0} -- YES --> OUTN[PRINT: negative number.] --> E((END))
IF1 -- NO --> IF2{IF number > 0} -- YES --> OUTP[PRINT: positive number.] --> E
IF2 -- NO --> OUT0[PRINT: number zero.] --> E
```
