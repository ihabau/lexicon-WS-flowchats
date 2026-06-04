## 14. Login System (Maximum 3 Attempts)

Create an algorithm and flowchart for a login system that allows a user
up to 3 attempts to enter the correct password. Display **"Access
Granted"** if the password is correct; otherwise display **"Account
Locked"** after 3 failed attempts.

---

### ✔ Pseudocode

```
START
  SET: attempts = 3, passRec = 12345
  INPUT: password
  IF: password == passRec
    PRINT: Access Granted.
  ELSEIF
    attempts > 0
      attempts -= 1
      PRINT: PRINT: TRY AGAIN.
  ELSE
    PRINT: Account Locked.

END
```

### ✔ Flowchart

```mermaid
flowchart LR
S((START)) --> SET["`SET: attempts = 3
passRec = 12345`"]
SET --> IN[/Inter password/]
IN --> IF1{password == passRec} -- YES --> OUT1[/PRINT: Access Granted./] --> E((END))
IF2 -- NO --> OUT3[/PRINT: ACCESS DENIED./] --> E
IF1 -- NO --> INC[attempts -= 1] --> IF2{attempts > 0} -- YES -->  OUT2[/PRINT: TRY AGAIN./] --> IN
```

```mermaid
flowchart TD
S((START)) --> SET["`SET: attempts = 3
passRec = 12345`"]
SET --> IN[/Inter password/]
IN --> IF1{password == passRec} -- YES --> OUT1[/PRINT: Access Granted./] --> E((END))
IF2 -- NO --> OUT3[/PRINT: ACCESS DENIED./] --> E
IF1 -- NO --> INC[attempts -= 1] --> IF2{attempts > 0} -- YES -->  OUT2[/PRINT: TRY AGAIN./] --> IN
```
