english-words
=============

Fixed version of https://github.com/dwyl/english-words

Merged all the files into 3 specific file types for easier use 

1. sorted_merged	- Line numbers = 1070701

    This file contains all of the original 3 files merged into one and
    then sorted, this file is Upper and lower case so there is duplicates.
    
2. lower_no-dups	- Line numbers = 466920

    This version has all of the words converted to lower case and then the
    duplicates removed, useful for when application isnt case sensitive
    
3. lower_no-dups-no-sym	- Line numbers = 466920

    same as the previous file but all symblos have been removed, this 
    file contains only alphanumeric values

RAW - Links
=============

sorted_merged
https://raw.githubusercontent.com/d0t1q/english-words/master/sorted_merged

lower_no-dups
https://raw.githubusercontent.com/d0t1q/english-words/master/lower_no-dups

Lower_no-dups-no-sym
https://raw.githubusercontent.com/d0t1q/english-words/master/lower_no-dups-no-sym


Previous Readme notes(depreciated now)
-------------
While searching for a list of english words (for an auto-complete tutorial)
I found: http://stackoverflow.com/questions/2213607/how-to-get-english-language-word-database which refers to http://www.infochimps.com/datasets/word-list-350000-simple-english-words-excel-readable 

No idea why infochimps put the word list inside an excel (.xls) file.

I pulled out the words into a simple new-line-delimited text file.
Which is more useful when building apps or importing into databases etc.

Copyright still belongs to them. 
