## compare(), making filter() fun again 
Originally published: 2008-10-04 14:27:27 
Last updated: 2008-10-04 12:40:42 
Author: Andreas Nilsson 
 
compare() takes a function parameter and returns a callable comparator when compared to a value. When called, the comparator returns result of comparing the result of calling the function and the value it was created with.