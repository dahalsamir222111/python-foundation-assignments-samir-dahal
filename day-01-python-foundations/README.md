# Day 1: Python Foundations

## Exercises Completed

1. ✅ Sales Summary
2. ✅ Data Quality Checker
3. ✅ File Validator
4. ✅ Customer Record Cleaner
5. ✅ Pipeline Health Status
6. ✅ Dataset Access Decision

---

## What I Learned

- Using variables and data types in Python
- Performing calculations with arithmetic operators
- Formatting output using f-strings
- Using conditional statements (if-elif-else)
- Cleaning and formatting strings with methods like strip(), title(), lower()
- Validating file extensions
- Implementing logic for data quality checks

---

## Common Challenges & Solutions

### Challenge 1: f-string formatting
**Problem:** Forgetting to use `:.2f` to show 2 decimal places for currency.
**Solution:** Always use `{variable:.2f}` when displaying money values.

### Challenge 2: String methods order
**Problem:** Using `.title()` before `.strip()` doesn't clean spaces properly.
**Solution:** Always use `.strip()` first, then other methods like `.title()` or `.lower()`.

### Challenge 3: Input validation
**Problem:** User enters "SALES.CSV" and it doesn't match ".csv".
**Solution:** Always use `.lower()` to convert input to lowercase before checking.

### Challenge 4: Multiple conditions
**Problem:** Getting confused with `and` vs `or` in if statements.
**Solution:** Remember: `and` means BOTH conditions must be true, `or` means AT LEAST ONE must be true.

### Challenge 5: Ternary operators
**Problem:** Ternary expressions look confusing at first.
**Solution:** Think of it as: `value_if_true if condition else value_if_false`

---

## Tips for Beginners

1. **Always clean your input** - Use `.strip()` to remove unwanted spaces
2. **Convert to lowercase** - Makes string comparison easier with `.lower()`
3. **Use f-strings** - They make output formatting much cleaner
4. **Test with different inputs** - Don't just test with the given values
5. **Read error messages** - They tell you exactly what's wrong

---

## My Solutions

Check the individual exercise files to see my solutions:
- `exercise-01-sales-summary.py`
- `exercise-02-data-quality-checker.py`
- `exercise-03-file-validator.py`
- `exercise-04-customer-cleaner.py`
- `exercise-05-pipeline-health.py`
- `stretch-access-decision.py`
