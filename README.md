# babynames_analysis
## Overview
This program visualizes the data of the ranking of English names. It contains a user interface that user can enter names, and the program will show the ranking of the name and draw the run chart shown as below.

<img src="https://github.com/Evian-Chen/babynames_analysis/blob/main/namesGraph.png" width="500" height="320">

The top-left bar is for searching name. If the name does not exist in the data list, the top-right bar will show the notice.
The bottom-left id for searching sub-name. Enter a sub-string, the bottom-right bar will show all names that contains the sub-string.

The data looks like:
<img src="https://github.com/Evian-Chen/babynames_analysis/blob/main/dataList.png" width="400" height="160">

The first line is the year, the first number is ranking.(There are 1000 rankings)

The following are man and female names.

## Methodology
* Read in all file and put them into dictionary.
* Make functions to search names.
* Make graphics.

## References
<a href="https://www.ssa.gov/OACT/babynames/">Top 10 Baby Names of 2022</a>
