# SQLquestion32
What is Case WHEN in SQL?


Control statements form an important part of most languages since they control the execution of other sets of statements. These are found in SQL too and should be exploited for uses such as query filtering and query optimization through careful selection of tuples that match our requirements. In this post, we explore the Case-Switch statement in SQL. The CASE statement is SQL’s way of handling if/then logic.

syntax: 1
CASE case_value
    WHEN when_value THEN statement_list
    [WHEN when_value THEN statement_list] ...
    [ELSE statement_list]
END CASE
syntax: 2
CASE
    WHEN search_condition THEN statement_list

    [WHEN search_condition THEN statement_list] ...
    [ELSE statement_list]
END CASE
