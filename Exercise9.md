## 9. Calculate Factorial of a Number

Write the algorithm and draw the flowchart that input a number and
calculate its factorial using a loop.

---

**input style:**

### ✔ Pseudocode

```
START
  IN[/number/]
  IF number <= 0
    PRINT: undefined factorial.
  ELSE
    SET: res = number
    SET: counter = number
    WHILE counter > 1
      counter -= 1
      res = res * counter
    ENDWHILE
    PRINT: res
  ENDIF
END
```

### ✔ Flowchart

```mermaid
flowchart LR
S((START)) --> IN[/input number/]
IN --> IFUD{if number <= 0} -- YES --> OUTUN[/PRINT: undefined factorial/]
IFUD -- NO --> SET{{"`SET: res = number,
counter = number`"}}
SET --> LOOP{counter > 1} -- NO --> PRINT[/print: res/] --> E((END))
LOOP -- YES --> INC[counter -= 1] --> CALC[res = res * counter]
CALC --> LOOP
```

```mermaid
flowchart TD
S((START)) --> IN[/input number/]
IN --> IFUD{if number <= 0} -- YES --> OUTUN[/PRINT: undefined factorial/]
IFUD -- NO --> SET{{"`SET: res = number,
counter = number`"}}
SET --> LOOP{counter > 1} -- NO --> PRINT[/print: res/] --> E((END))
LOOP -- YES --> INC[counter -= 1] --> CALC[res = res * counter]
CALC --> LOOP
```
