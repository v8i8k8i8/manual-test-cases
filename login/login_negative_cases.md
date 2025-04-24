# Login - Negative Test Cases

| ID     | Scenario                    | Steps                                              | Expected Result                      |
|--------|-----------------------------|----------------------------------------------------|--------------------------------------|
| TC-101 | Empty fields                | Leave email and password empty, click login        | Error: 'Please enter credentials'    |
| TC-102 | Invalid password            | Enter correct email, wrong password                | Error: 'Invalid credentials'         |
