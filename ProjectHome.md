Caution: before considering this code, please read [Parsing CSV while staying within the “total number of executed script statements” governor limit](http://force201.wordpress.com/2010/08/12/parsing-csv-while-staying-within-the-total-number-of-executed-script-statements-governor-limit/) and all the comments on that post.

What is really needed is for Salesforce to add an API that gets CSV files parsed without consuming the "total number of script statements" governor limit. This code will only work in limited circumstances.

For information on features and how to use the code, see [opencsv](http://opencsv.sourceforge.net/), the Java project this code was ported from.