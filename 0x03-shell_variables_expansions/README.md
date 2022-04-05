# Understanding Shell Initialization files

## The Concept Below will be Examine

* The concept of Expansion : What is expansions

* Undertanding how shell prcocess shell arithmetics

* Understanding variables - The concept of global and local variable.

* Using the Alias command
Commands

set : The set command is a built in linux shell comm
How to add a directory to the PATH environment variables:
* Adding path to the begininging of the path -

    export PATH=$PATH"""::


Global variables are also called environment variables which will be available to all shells, printenv command is used to display all the environment variables

Local variables are visible only within the block of code. local is a keyword which is used to declare the local variables. in a function, a local variable has meaning only within that funciton block.

local variables are only availble in the current shell. set command without option will display a list of all variable(including environment and functions

set : when used without option display list of local variables, functions and global variable.

unset : unassign the value of a variable

* Variables that are exported are referred to as environment variables. setting and exporting is usually done in one step.
    export VARNAME="value"
