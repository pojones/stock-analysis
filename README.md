# stock-analysis

##Purpose
The purpose of this project was to refactor a piece of VBA code to run more efficiently. The code itself observes various stock opportunities and analyzes them over 2017 and 2018 to explore which companies might be worth investing in.

##Results
Almost everyone was getting positive returns in 2017. The only two companies to continue the trend in 2018 were ENPH and RUN. RUN and TERP were the only companies to increase their percentage returns from 2017 to 2018, however TERP posted straight losses both years. The execution times of the refactored code was quicker by a factor of seven or greater. Run time for the unoptimized code was anywhere from .8 to .85 seconds, whereas the refactored code ran in the .1 to .13 range. This is a significant improvement.

##Summary 
The obvious advantage of refactoring code is that it is much quicker to execute. For particularly large datasets, this is crucial. Additionally, the refactored code is generally easier to read, and more pleasant to look at. This is helpful for teams that have to collaborate on a single piece of code. The disadvantage is that the refactored code generally is an additional iteration of a program that’s already been written. Meaning that refactoring is technically more work than just getting it right the first time. 
As it pertains to our project, the quicker execution was the sought-after result. As far as doing more work, that was inevitable in this academic case. 

