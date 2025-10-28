- Basic Postgres functions:

- Date functions:

  1. Get week from date: extract(week from date_column)
  2. Get week from date for a particular month: extract(week from date_column) - extract(week from '2025-01-10':: date)+ 1
  3. get seconds/epoch difference from 2 dates: extract(epoch from d1-d2)
  4. get minutes difference from 2 dates:extract(epoch from d1-d2)/60
 
- Genrate series:
  select generate_series( min_val, max(val))
  
