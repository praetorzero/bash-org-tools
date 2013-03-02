# Bash.org scrape

Bash.org is basically the aphorisms of the internet and as far as I'm concerned it has languished.

This is a scrape, database, and fortune file of bash.org taken on March 1, 2013.  It has all the approved quotes - the removed quotes in txt format.

Each quote is a result of a `links -dump` command and has the following format:

    #(quote number) +(score)- [x]
    quote

For instance:

    #5273 +(30077)- [X]
    <erno> hm. I've lost a machine.. literally _lost_. it responds to ping, it works completely, I just can't figure out where in my apartment it is.

## Goodies

in tools/ there is

 * a program that creates an SQLite3 database out of the quotes
 * a script that creates a fortune(6) database from this database with a minimum threshhold.

In fortune/ this database is there.
