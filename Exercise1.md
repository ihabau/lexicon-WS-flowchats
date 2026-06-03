## 1. Check Even or Odd Number

Design an algorithm and flowchart that take a number as input and
determine whether it is even or odd.

### ✔ Pseudocode

```
START
  INPUT number
  IF number % 2 == 0
      PRINT Even
  ELSE
      PRINT Odd
  ENDIF
END
```

### ✔ Flowchart

```mermaid
flowchart TD
S((Start)) --> IN[/NUM = Input a number/]
IN --> IF{NUM % 2 == 0} -- YES --> PRINT-E[/Print Even/] --> END((END))
IF -- NO --> PRINT-O[/print Odd/] --> END
```
