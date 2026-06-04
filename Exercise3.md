## 3. Display Multiplication Table

Create an algorithm and flowchart that input a number and display its
multiplication table from 1 to 10 using a loop.

---

### ✔ Pseudocode

```
START
  INPUT number
  SET counter 1
  WHILE counter <= 10
     set res = number * counter
     print res
     counter += 1
  ENDWHILE
END
```

### ✔ Flowchart

```mermaid
flowchart LR
S((START)) --> INPUT[/input: number/]
INPUT --> COUNTER[counter = 1]
COUNTER --> LOOP{WHILE: counter <= 10}
LOOP -- NO --> E((END))
LOOP -- YES --> CALC[res = input * counter]
CALC --> OUTPUT[/print: res/]
OUTPUT --> INC[counter += 1]
INC -- LOOP --> LOOP
```

```mermaid
flowchart TD
S((START)) --> INPUT[/input: number/]
INPUT --> COUNTER[counter = 1]
COUNTER --> CALC[res = input * counter]
CALC --> INC[counter +=  1]
INC --> OUTPUT[/print: res/]
OUTPUT --> IF{WHILE: counter <= 10}
IF -- YES --> CALC
IF -- NO --> E((END))
```
