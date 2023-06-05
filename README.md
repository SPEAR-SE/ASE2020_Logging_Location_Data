# ASE2020 Logging Location Data

This is the repository containing the replication package for paper "Where Shall We Log? Studying and Suggesting Logging Locations in Code Blocks". 

- `LoggingStatement.zip` contains the logging statements with their related information extracted from the studied systems. For each line of logging statement:
    - `logcall` represents for the logging library that a logging statement invokes
    - `parameter` lists all the parameters of this logging statement (including static message and dynamic variables)
    - `constant` shows the static message of a logging statement
    - `level` shows the verbosity level of this logging statement
    - `callsite` represents for the class and method of that this logging statement locates in
    - `line` shows the line number that this logging statement locates at

- `where_to_log_code.zip` contains the code related to this paper.
