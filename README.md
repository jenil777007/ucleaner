# ucleaner
Repo of Ubuntu System Cleaner
NAME
       ucleaner - A cron tab cleaner

SYNOPSIS
       sudo ucleaner

DESCRIPTION
       ucleaner is a basic shell script for cleaning up your system. It cleans
       up the system buffer, cache , trash and old kernels. Basically  it's  a
       cron  job  but anyone can perform it with the help of command. In order
       to set up the cron job :-
       1) Type crontab -e in the Terminal.
       2) At the end of the file append the specific time on  which  you  want
       system  to  perform  cleanup.  The syntex of cron tab is minute(0 - 59)
       hour(0 - 23) dateofmonth(1 - 31) month(1 - 12) dayofweek(0 - 6) command
       eg. at 5 a.m every week type in 0 5 * * 1 followed by the source of the
       shell script.

OPTIONS
       The  ucleaner does not take any options. However, root access is neces‐
       sary.

BUGS
       No known bugs.

AUTHOR
       Jenil Calcuttawala(13bce015@nirmauni.ac.in)
       Akshay Chaudhari(13bce006@nirmauni.ac.in)
