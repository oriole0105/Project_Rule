
Project Coding Style Rule
=========================

Those rules are created for project management.
All members shoule follow this rules.


For compile: No syntax error is enough.


For corder: add comment to make sure you still understand the code after serval
months later.


For other people: add comment to explain the idea



Rule Maker
==========

* Richard Luo ( richard_luo@phison.com )

Rule Groups
===========

* File
* Verilog Coding Style
** Common rule

File
====

* one module per file
* filename MUST the same as the module name

Verilog Coding Style
====================

Common Rule
-----------

* Don't use "TAB". Use whitespace replace it.
* Indent as 4 whitespace.


example 1
    
    if ( condition1 )
    begin
        a = b;
    end
    else if ( condition2 )
    begin
        a = d;
    end
    else
    begin
        a = 1;
    end

example 2

    if ( condition1 ) begin
        a = b;
    end
    else if ( condition2) begin
        a = d;
    end
    else begin
        a = 1;
    end



Reference
=========

* [Markdown](http://markdown.tw)
* [Linux Coding Sytle](http://lxr.linux.no/linux/Documentation/CodingStyle)


