# Oracle-Listagg-Distinct
A custom PL/SQL TYPE and FUNCTION designed to concatenate unique strings in an Oracle SQL Query.

For example, with a table of content:

ID    NAME
1     Jake
2     Justin
3     Mary
4     Mary
5     Joe

The SQL query, select listagg_distinct(NAME) from table_name, would return:

Jake, Justin, Mary, Joe
