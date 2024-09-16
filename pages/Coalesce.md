- Takes first non-[`NULL`]([[Null]])  value
- ```sql
  SELECT COALESCE(1, NULL) ------ 1
  SELECT COALESCE(NULL, 3) ------ 3
  SELECT COALESCE(1, 2) --------- 1
  SELECT COALESCE(NULL, NULL) --- NULL
  ```
- Natural full joins model `COALESCE`
  id:: 66e857ff-ca1c-4179-bee6-9f020a647fba
- ```sql
  M = {(a: [1, 2])}
  N = {(a: [2, 3])}
  
  SELECT *
  FROM M
  NATURAL FULL JOIN N
  
  --- {(a: 1, 2, 3)}
  ```
- [Abiteboul 1995]([[abiteboul1995foundations]])