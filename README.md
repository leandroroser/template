# PUBLICATION TITLE

**AUTHOR**

**PUBLICATION URL**

Brief summary of the repo


## REPOSITORY STRUCTURE

Run this command in bash in the repository folder and paste the output:

#!/bin/bash

#File: tree-md

tree=$(tree -tf --noreport -I '*~' --charset ascii $1 |
       sed -e 's/| \+/  /g' -e 's/[|`]-\+/ */g' -e 's:\(* \)\(\(.*/\)\([^/]\+\)\):\1[\4](\2):g')

printf "# Project tree\n\n${tree}"

## USAGE

Describe how to use this repo

## SAMPLE DATA USED IN THE PUBLICATION

Briefly describe origin of the data and how it was collected. Links if necessary. Include the data within this repo, if needed in a separate folder in relation the main programs.

### DATA STRUCTURE

- Col1 : description of column - data type (str). If needed example, such as #AB424C
- Coln ....



