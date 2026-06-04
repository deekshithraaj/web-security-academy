# SQL Injection

## Lab

PortSwigger SQL Injection Labs

## Objective

Learn SQL Injection techniques and bypass filters.

## Payloads

```sql
' OR 1=1--
```

## Notes

- SQL Injection occurs when user input is concatenated into SQL queries.
- Parameterized queries help prevent SQL Injection.
- Always validate and sanitize input.
