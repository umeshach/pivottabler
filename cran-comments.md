## Background

This is a new package written entirely in R with no external dependencies/components other than the packages listed in the  DESCRIPTION file.
Development approach is aligned with practices described in:
http://r-pkgs.had.co.nz/

## Test environments

* local OS (windows) install, R 3.3.3
* ubuntu 12.04 (on travis-ci), R 3.3.2.
* win-builder, R 3.4.0 alpha 

## R CMD check results

### Local R CMD check results

0 errors | 0 warnings | 0 notes

### Travis-CI R CMD check results

0 errors | 0 warnings | 1 note

NOTE:  
  installed size is  5.0Mb,
  sub-directories of 1Mb or more:
    data   3.9Mb

Unsure of reason for discrepancy between Local R CMD and Travis-CI CMD check results. The sample data has been compressed into three rda files, total size 1.00 MB. Different compression options were explored and the option chosen that resulted in the smallest files.

### win-builder check results

0 errors | 0 warnings | 1 note

NOTE:  New Submission

## Downstream dependencies

None - this is a new package.
