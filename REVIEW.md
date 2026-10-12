# REVIEW.md

List every defect you found in the starter `app/main.py` (helpers and endpoints). For each one:

| # | Where (function / line) | What is wrong | How you'd notice it (test, input, or symptom) | How you fixed it |
|---|---|---|---|---|
| 1 | health()|Returned success without checking MongoDB connection. |Returned 200 ok when MongoDB was unreachable |Added MongoDB ping, DB returns 503 error if unreachable |

Also note anything you looked at and decided was **not** a defect, and why.
