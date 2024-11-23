# Bank Marketing Dataset

## Input Variables:

### Bank Client Data:
1. **age**: Age of the client (numeric)
2. **job**: Type of job (categorical)
   - Values: `"admin."`, `"unknown"`, `"unemployed"`, `"management"`, `"housemaid"`, `"entrepreneur"`, `"student"`, `"blue-collar"`, `"self-employed"`, `"retired"`, `"technician"`, `"services"`
3. **marital**: Marital status (categorical)
   - Values: `"married"`, `"divorced"`, `"single"`
   - Note: `"divorced"` includes both divorced and widowed.
4. **education**: Level of education (categorical)
   - Values: `"unknown"`, `"secondary"`, `"primary"`, `"tertiary"`
5. **default**: Has credit in default? (binary)
   - Values: `"yes"`, `"no"`
6. **balance**: Average yearly balance in euros (numeric)
7. **housing**: Has housing loan? (binary)
   - Values: `"yes"`, `"no"`
8. **loan**: Has personal loan? (binary)
   - Values: `"yes"`, `"no"`

### Related to the Last Contact of the Current Campaign:
9. **contact**: Contact communication type (categorical)
   - Values: `"unknown"`, `"telephone"`, `"cellular"`
10. **day**: Last contact day of the month (numeric)
11. **month**: Last contact month of the year (categorical)
    - Values: `"jan"`, `"feb"`, `"mar"`, ..., `"nov"`, `"dec"`
12. **duration**: Duration of the last contact in seconds (numeric)

### Other Attributes:
13. **campaign**: Number of contacts performed during this campaign and for this client (numeric, includes the last contact)
14. **pdays**: Number of days since the client was last contacted from a previous campaign (numeric)
    - Value `-1` means the client was not previously contacted.
15. **previous**: Number of contacts performed before this campaign for this client (numeric)
16. **poutcome**: Outcome of the previous marketing campaign (categorical)
    - Values: `"unknown"`, `"other"`, `"failure"`, `"success"`

## Output Variable (Target):
17. **y**: Has the client subscribed to a term deposit? (binary)
    - Values: `"yes"`, `"no"`

