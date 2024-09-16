- TODO [#A] Testing tasks 
  DEADLINE: <2024-09-17 Tue 12:00>
  :LOGBOOK:
  CLOCK: [2024-09-17 Tue 01:11:41]--[2024-09-17 Tue 01:11:42] =>  00:00:01
  CLOCK: [2024-09-17 Tue 01:12:19]--[2024-09-17 Tue 01:12:19] =>  00:00:00
  :END:
- TODO [#C] Modify the footnotes plugin
- TODO [#C] Block aliasing is definitely a feature I'd want to keep a track of
- TODO [#C] Read Michael Neilson's article on [Augmenting Long Term Memory](http://augmentingcognition.com/ltm.html)
- Takes first non-[`NULL`]([[Null]])  value 
  ```sql
  SELECT COALESCE(1, NULL) ------ 1
  SELECT COALESCE(NULL, 3) ------ 3
  SELECT COALESCE(1, 2) --------- 1
  SELECT COALESCE(NULL, NULL) --- NULL
  ```
- Natural full joins model `COALESCE` 
  id:: 66e857ff-ca1c-4179-bee6-9f020a647fba
  ```sql
  M = {(a: [1, 2])}
  N = {(a: [2, 3])}
  
  SELECT *
  FROM M
  NATURAL FULL JOIN N
  
  --- {(a: 1, 2, 3)}
  ```
- [Abiteboul 1995]([[abiteboul1995foundations]])
- [[Foundations of Databases]]
-
- #+BEGIN_QUOTE
  This is a quote bro!
  #+END_QUOTE
- #+BEGIN_NOTE
  Note
  #+END_NOTE
- #+BEGIN_CAUTION
  Throw caution to the wind!
  #+END_CAUTION
- #+BEGIN_EXAMPLE
  This be an example
  #+END_EXAMPLE
- <% current time %>
- This is a block
	- alias:: An alias for the block
	- Content of the block
- [[An alias for the block]]