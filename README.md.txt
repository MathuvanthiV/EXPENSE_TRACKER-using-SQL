# Expense Tracker SQL Project

## Description
This is a beginner-friendly SQL project to track user expenses. 
It demonstrates:
- Aggregation (SUM, COUNT, AVG)
- Grouping (GROUP BY)
- Filtering (WHERE, HAVING, BETWEEN)
- Joins (INNER JOIN, LEFT JOIN)
- Ranking and OFFSET
- Date formatting (strftime)

## Database
- SQLite database file: `expense_tracker.db`
- Tables:
  - `users(user_id, name)`
  - `expenses(expense_id, user_id, amount, category, expense_date, description)`

## Queries
- queries.sql file contains 12 SQL queries:
  1. Total spending per user
  2. Category-wise total spending
  3. Highest spending user
  4. Highest spending day
  5. Expenses above average
  6. Users spending more than X
  7. Monthly spending per user
  8. Users with no expenses
  9. Most frequent expense category
  10. Top 3 users by total spending
  11. Second highest spender
  12. Expenses between two dates
