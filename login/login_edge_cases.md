# Login - Edge Cases

| ID     | Scenario                      | Steps                                                       | Expected Result                    |
|--------|-------------------------------|-------------------------------------------------------------|------------------------------------|
| TC-201 | Email with trailing space     | Enter email with trailing space                             | System should trim and log in      |
| TC-202 | Long email & password strings | Use max allowed characters for both fields                  | Login works or error message shown |
