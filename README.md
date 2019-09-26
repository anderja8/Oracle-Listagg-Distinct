# Oracle-Listagg-Distinct
A custom PL/SQL TYPE and FUNCTION designed to concatenate unique strings in an Oracle SQL Query.

I made this function so that I could obtain in the listagg functionality when querying an SQL database at work, but only concatenate distinct values. I've found it to be very helpful. By default it inserts ", " between each concatenated string.

I found this post to be extremely helpful when building this function:
https://www.experts-exchange.com/articles/9391/How-to-Create-User-Defined-Aggregates-in-Oracle.html
