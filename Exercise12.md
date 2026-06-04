## 12. Employee Salary and Bonus Calculator

Write the algorithm and draw the flowchart for a program that inputs an
employee's monthly salary and years of service, calculates a bonus of
**10%** for employees with 5 or more years of service and **5%** for
others, then displays the bonus and total salary.

---

### ✔ Pseudocode

```
START
  INPUT: sal, years
  SET: bonus, totalSal
  IF: years >= 5
    bonus = sal * 0.1
  ELSE:
    bonus = sal * 0.05
  ENDIF
  totalSal = sal * 09
  PRINT: totalSal, bonus
END
```

### ✔ Flowchart

```mermaid
flowchart LR
S((START)) --> IN[/Input: sal, years/]
IN --> SET[SET: bonus = 0, totalSal = 0]
SET --> IF{years >= 5}
IF -- YES --> calc10["`SET:bonus = sal * 0.1
totalSal = sal + bonus`"] --> OUT[/PRINT: totalSal, bonus/] --> E((END))
IF -- NO --> calc05["`SET:bonus = sal * 0.05
totalSal = sal + bonus`"] --> OUT
```

```mermaid
flowchart TD
S((START)) --> IN[/Input: sal, years/]
IN --> SET[SET: bonus = 0, totalSal = 0]
SET --> IF{years >= 5}
IF -- YES --> calc10["`SET:bonus = sal * 0.1
totalSal = sal + bonus`"] --> OUT[/PRINT: totalSal, bonus/] --> E((END))
IF -- NO --> calc05["`SET:bonus = sal * 0.05
totalSal = sal + bonus`"] --> OUT
```
