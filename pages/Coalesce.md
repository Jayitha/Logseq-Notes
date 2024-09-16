- TODO [#A] Testing tasks 
  DEADLINE: <2024-09-17 Tue 12:00>
  :LOGBOOK:
  CLOCK: [2024-09-17 Tue 01:11:41]--[2024-09-17 Tue 01:11:42] =>  00:00:01
  CLOCK: [2024-09-17 Tue 01:12:19]--[2024-09-17 Tue 01:12:19] =>  00:00:00
  :END:
- TODO [#C] Modify the footnotes plugin
- TODO [#C] Block aliasing is definitely a feature I'd want to keep a track of
- TODO [#C] Read Michael Neilson's article on [Augmenting Long Term Memory](http://augmentingcognition.com/ltm.html)
- TODO [#C] Tables and drawing do not preview
	- In fact, I can't even reference a table block?
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
- [[draws/2024-09-17-02-04-04.excalidraw]]
  id:: 66e890ef-3a7f-4451-8423-fc1cd6f649f9
-
- ```calc
  3 + 4
  ```
- ```calc
  x = 2
  y = 3
  x + y
  ```
- ![Foundations of Databases](http://webdam.inria.fr/Alice/pdfs/all.pdf)
  id:: 66e896e6-564b-4c30-aa0d-9c7ac826e7ee
	- ((66e89784-72d6-40ff-8005-ea16e544e28f))
- TODO [#C] Is it possible for me to add links from my personal (private) google drive?
- TODO [#B] [Advanced Datalog Queries](https://docs.logseq.com/#/page/advanced%20queries)
- $x^2$
- $$x^2$$
- \begin{aligned}a + b = 2\end{aligned}
-
- id:: 66e89f49-fe92-45b3-b2fe-34348a404456
  | title 1 | title 2 |
  |Testing tables|Seems to work|
-
- Nice, you can ^^highlight^^ text
-