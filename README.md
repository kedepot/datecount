# datecount
Calculate days + other units of time between input dates
  
![datecount](https://github.com/kedepot/datecount/assets/95410139/baa683f5-ad32-4696-9de7-86d040a1b619)

**Format:** datecount 1989-10-03 2023-10-03<br>
(Year-Month-Day. Not tested with non-ISO8601 locales - may or may not work on those.) 

- Hyphens are not required
- If only a single date is provided, **today** is used as 'to' date
- Only using the last 2 digits of a year will be counted as 1900's
  
