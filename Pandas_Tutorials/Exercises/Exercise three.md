# Adding New Columns

## Task 1: Create a New Column `HourlyWage`
Create a new column `HourlyWage` by dividing `ConvertedComp` by `(WorkWeekHrs * 52)`. This calculates the approximate hourly wage of respondents based on their annual compensation and average weekly work hours.

## Task 2: Add a Boolean Column `IsSenior`
Add a new boolean column `IsSenior` where the value is `True` if `YearsCodePro` is greater than 10, otherwise `False`. This identifies respondents with significant professional coding experience.

---

### Instructions:
1. Write Python code to accomplish the tasks.
2. Ensure you understand the logic before attempting.
3. Use `apply` and lambda functions where necessary.

### Additional Notes:
- Handle missing or invalid data by ensuring all required columns are numeric using `pd.to_numeric`.
- Test the calculations with a subset of the data to verify accuracy before applying to the entire DataFrame.

---

### Check Solution Here:
[Solution on Google Colab](https://colab.research.google.com/drive/1T2zBIyvLoqCKmw4k-vlrYQTCVEorm-Ce?usp=sharing)



