# SQL for all

### - Type of comments
We use comments for explain, detail and mark certain parts of our code.
>
Single Line comments (--Write your comment here)
>
Multi-line comments: /* Write your comment here* /


### - Type of conditions:
We use conditions for filter data search.

<!-- First condition-->
* 'OR' Condition:
We use 'OR' for comparisons, the best would be 'This or that'
>
Select * from title.database where (jobposition = 'Analyst') or (jobposition = 'Operator');

<!-- Second condition-->
* AND Condition:
We use 'AND' when two conditions are required
>
Select * from title.database where (lower(first.name)='first name') and (lower(last.name)='last name');

<!-- Third condition-->
* NOT Condition:
We use 'NOT' condition to rule out options.
>
Select * from title.database where NOT (lower(first.name)='carlos');