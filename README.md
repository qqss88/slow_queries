# slow_queries
research on slow queries

query1: two names with cycle
name1='Vavic', name2='Vandemoer', two_year_transaction=2018

query2: two names, no cycle
name1='Vavic', name2='Vandemoer'

query3: one name with cycle
name = 'Vavic', two_year_transaction=2018

query4: one name with cycle
name = 'Vandemoer', two_year_transaction=2018

result summary:
only query 1 does NOT run BITMAP INDEX SCAN on names  
