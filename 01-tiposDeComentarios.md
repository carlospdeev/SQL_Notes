# SQL for all

### - Type of comments
We use comments for explain, detail and mark certain parts of our code.
>
Single Line comments (--Write your comment here)
>
Multi-line comments: /* Write your comment here* /


### - Type of conditions:
We use conditions for filter data search.

* 'OR' Condition:
We use 'OR' for comparisons, the best would be 'This or that'
>
Select * from title.database where (jobposition = 'Analyst') or (jobposition = 'Operator');

* AND Condition:
We use 'AND' when two conditions are required
>
Select * from title.database where (lower(first.name)='first name') and (lower(last.name)='last name');

* NOT: 