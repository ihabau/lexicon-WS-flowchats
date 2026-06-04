## 10. Calculate Discount on Purchase

Write the algorithm and draw the flowchart for a program that inputs the
purchase amount and gives a **10% discount** if the amount is greater
than 1000.

---

### ✔ Pseudocode

```
START
  INPUT: amount
  SET: finalPrice = amount
  IF: amount > 1000
    finalPrice = amount * 0.9
  ENDIF
  OUT: print finalPrice
END
```

### ✔ Flowchart

```mermaid
flowchart LR
S((START)) --> IN[/INPUT: amount/]
IN --> SET{{finalPrice = amount}}
SET --> IF{amount > 1000}
IF -- YES --> RES1[finalPrice = amount * 0.9]
RES1 --> OUT[/PRINT: finalPrice/]
IF -- NO --> OUT --> E((END))
```

```mermaid
flowchart TD
S((START)) --> IN[/INPUT: amount/]
IN --> SET{{finalPrice = amount}}
SET --> IF{amount > 1000}
IF -- YES --> RES1[finalPrice = amount * 0.9]
RES1 --> OUT[/PRINT: finalPrice/]
IF -- NO --> OUT --> E((END))
```
