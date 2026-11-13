Task B2 – Adversarial Testing and SQL Injection Safety

Aim

To test the reliability and security of the air quality data processing system using adversarial inputs and SQL injection testing.

Problem Statement

Input data may contain missing columns, empty values, invalid formats and malicious SQL commands. These inputs can cause errors or security problems. This task tests how the system handles such situations safely.

Tools Used

- Python
- SQLite3
- CSV Module

Concepts Used

- Adversarial testing
- Input validation
- Error handling
- SQL injection prevention
- Parameterized SQL queries
- Empty input handling
- Invalid data detection

Program Files

1. "sql_safety.py"
2. "adversarial_tests.py"

Steps to Execute

1. Open the Python environment.
2. Run "sql_safety.py".
3. Check whether the SQL injection attempt is prevented.
4. Run "adversarial_tests.py".
5. Verify the test results.

Expected Output

- SQL injection attempt is prevented.
- Missing columns are detected.
- Empty input is handled.
- Invalid numeric values are rejected.
- Valid input is accepted.
- Adversarial tests are completed successfully.

Conclusion

The programs demonstrate secure SQL query handling and effective input validation. Parameterized queries help prevent SQL injection attacks and adversarial testing improves the reliability of the system.
