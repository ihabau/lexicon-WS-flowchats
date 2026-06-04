## 13. Mobile Data Usage Monitor

Write the algorithm and draw the flowchart for a program that inputs a
user's monthly data limit and data usage, then displays whether the user
has exceeded the limit or how much data remains.

---

### ✔ Pseudocode

```
START
  INPUT: dataLimit, dataUsage
  IF: dataUsage > dataLimit
    CALC: overflow = dataUsage - dataLimit
    PRINT: You have exceeded the data limit by, overflow
  ELSEIF: dataUsage == dataLimit
    PRINT: You have no more data.
  ELSE:
    CALC: dataLeft = dataLimit - dataUsage
    PRINT: dataLeft, data remains.
  ENDIF
END
```

### ✔ Flowchart

```mermaid
flowchart LR
S((START)) --> IN[/INPUT: dataUsage, dataLimit/]
IN --> IFOF{dataUsage > dataLimit} -- YES --> CALC1[overflow = dataUsage - dataLimit] --> OUT1[/PRINT: Data exceeded by, overflow/] --> E((END))
IFOF -- NO --> IF0{dataUsage == dataLimit} -- YES --> OUT2[/PRINT: No more data./] --> E
IF0 --NO --> CALC2[dataLeft = dataLimit - dataUsage] --> OUT3[/PRINT: dataLeft, data remains./] --> E
```

```mermaid
flowchart TD
S((START)) --> IN[/INPUT: dataUsage, dataLimit/]
IN --> IFOF{dataUsage > dataLimit} -- YES --> CALC1[overflow = dataUsage - dataLimit] --> OUT1[/PRINT: Data exceeded by, overflow/] --> E((END))
IFOF -- NO --> IF0{dataUsage == dataLimit} -- YES --> OUT2[/PRINT: No more data./] --> E
IF0 --NO --> CALC2[dataLeft = dataLimit - dataUsage] --> OUT3[/PRINT: dataLeft, data remains./] --> E
```
