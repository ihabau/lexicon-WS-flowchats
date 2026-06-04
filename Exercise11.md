## 11. Online Shopping Delivery Eligibility

Write the algorithm and draw the flowchart for a program that inputs a
customer's purchase amount and displays **"Free Delivery"** if the
amount is 500 SEK or more; otherwise display **"Delivery Charge
Applies"**.

---

### ✔ Pseudocode

```
START
  INPUT: amount
  IF: amount > 500
    PRINT: Free delivery.
  ELSE
    PRINT: Delivery charge applies.
  ENDIF
END
```

### ✔ Flowchart

```mermaid
flowchart LR
s((start)) --> in[/input: amount/]
in --> if{amount > 500}
if == yes -->out1[/print: free delivery./]
if == no -->out2[/print: delivery charge applies./]
out1 --> E((end))
out2 --> E
```

```mermaid
flowchart TD
s((start)) --> in[/input: amount/]
in --> if{amount > 500}
if == yes -->out1[/print: free delivery./]
if == no -->out2[/print: delivery charge applies./]
out1 --> E((end))
out2 --> E
```
