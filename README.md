# myrep
SMU Repository of Test Studies

CodeBook

The purpose of this file is to define the exploration of girls and boys names within this dataset. The key purpose is to define the top 10 girls names by sorting on the total of 2016 and 2015 data. The final dataset provides only those two 10 names which include:

##        Names Gender Count_2016 Count_2015 Total
## 1       Emma      F      19414      20415 39829
## 2     Olivia      F      19246      19638 38884
## 3     Sophia      F      16070      17381 33451
## 4        Ava      F      16237      16340 32577
## 5   Isabella      F      14722      15574 30296
## 6        Mia      F      14366      14871 29237
## 7  Charlotte      F      13030      11381 24411
## 8    Abigail      F      11699      12371 24070
## 9      Emily      F      10926      11766 22692
## 10    Harper      F      10733      10283 21016

To recreate this analysis, the following packages were used and software applications.

Packages used: 'dplyr', 'repmis', 'RCurl', 'tidyverse'
RStudio - Version 1.1.453
R version 3.7


Raw Data
yob2016.txt

'data.frame':    32869 obs. of  3 variables:
##  $ Names     : Factor w/ 30295 levels "Aaban","Aabha",..: 9317 22546 3770 26409 12019 20596 6185 339 9298 11222 ...
##  $ Gender    : Factor w/ 2 levels "F","M": 1 1 1 1 1 1 1 1 1 1 ...
##  $ COUNT_2016: int  19414 19246 16237 16070 14722 14366 13030 11699 10926 10733 ...

yob2015.txt

## 'data.frame':    33063 obs. of  3 variables:
##  $ Names     : Factor w/ 30553 levels "Aaban","Aabha",..: 9474 22858 26680 3771 12170 20927 344 9453 6252 11404 ...
##  $ Gender    : Factor w/ 2 levels "F","M": 1 1 1 1 1 1 1 1 1 1 ...
##  $ Count_2015: int  20415 19638 17381 16340 15574 14871 12371 11766 11381 10283 ...


Variables include

df      707 obs. of 6 var
y2016   33063 obs of 3 var
y2015   32868 obs of 3 var
dffind  32869 obs of 3 var
final   105200 obs of 4 var
girls   15267 obs of 5 var
sortFinal 106200 obs of 5 var
Top10   10 obs of 5 var
TTLFinal  106200 obs of 5 var

