APPEND vs APPENDCOLS

APPEND
You have two data sets with the exact set of columns (will work with non same columns sets
but you will get a mess on your hands)
[ data set A with columns f1,f2,...fn ] K lines
[ data set B with columns f1,f2,...fn ] M lines
K+M lines

APPENDCOLS
usually you want to the two data sets to have THE SAME NUMBER OF LINES
the DONT have to have the same colums or even the same number of columns
[ data set A with columns f1,f2,...fn ] K lines
[ data set B with columns g1,g2,...gm ] K lines

the result will have K lines
[ f1,f2,... fn, g1, g2,... gm]
[ f1,f2,... fn, g1, g2,... gm]
[ f1,f2,... fn, g1, g2,... gm]
[ f1,f2,... fn, g1, g2,... gm]
