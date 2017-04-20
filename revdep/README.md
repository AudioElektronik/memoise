# Setup

## Platform

|setting  |value                                  |
|:--------|:--------------------------------------|
|version  |R version 3.3.2 RC (2016-10-26 r71594) |
|system   |x86_64, darwin13.4.0                   |
|ui       |X11                                    |
|language |(EN)                                   |
|collate  |en_US.UTF-8                            |
|tz       |America/New_York                       |
|date     |2017-04-20                             |

## Packages

|package  |*  |version    |date       |source                           |
|:--------|:--|:----------|:----------|:--------------------------------|
|aws.s3   |   |0.2.2      |2017-04-20 |Github (cloudyr/aws.s3@305e9da)  |
|covr     |   |2.2.2      |2017-04-20 |Github (jimhester/covr@accef86)  |
|digest   |   |0.6.12     |2017-01-27 |cran (@0.6.12)                   |
|httr     |   |1.2.1      |2016-07-03 |cran (@1.2.1)                    |
|memoise  |   |1.0.0      |2016-01-29 |cran (@1.0.0)                    |
|testthat |   |1.0.2.9000 |2017-03-03 |Github (hadley/testthat@b72a228) |

# Check results

21 packages

|package        |version | errors| warnings| notes|
|:--------------|:-------|------:|--------:|-----:|
|biolink        |0.1.2   |      1|        0|     0|
|BWStest        |0.2.1   |      0|        0|     0|
|covr           |2.2.2   |      0|        0|     0|
|devtools       |1.12.0  |      0|        0|     0|
|functools      |0.2.0   |      0|        0|     0|
|GSED           |1.3     |      0|        0|     0|
|gWidgets2RGtk2 |1.0-5   |      1|        0|     0|
|gWidgets2tcltk |1.0-5   |      1|        0|     0|
|heemod         |0.9.0   |      0|        0|     0|
|icd9           |1.3.1   |      0|        0|     1|
|opencage       |0.1.0   |      0|        0|     0|
|OpenML         |1.3     |      0|        0|     0|
|prcbench       |0.7.3   |      0|        0|     1|
|regioneR       |1.6.2   |      0|        1|     4|
|rgho           |1.0.1   |      0|        0|     0|
|RSQLite        |1.1-2   |      0|        0|     0|
|saeRobust      |0.1.0   |      0|        0|     0|
|SamplingStrata |1.1     |      0|        0|     0|
|SIDES          |1.10    |      0|        0|     0|
|surveillance   |1.13.0  |      0|        0|     2|
|toaster        |0.5.5   |      0|        0|     0|

## biolink (0.1.2)
Maintainer: Aaron Wolen <aaron@wolen.com>

1 error  | 0 warnings | 0 notes

```
checking tests ... ERROR
Running the tests in ‘tests/testthat.R’ failed.
Last 13 lines of output:
     }) at /private/var/folders/dt/r5s12t392tb5sk181j3gs4zw0000gn/T/RtmpbeCFhk/devtools231b7fa9df2a/lintr/R/object_usage_linter.R:28
  18: FUN(X[[i]], ...)
  19: codetools::findFuncLocals(formals(fun), body(fun)) at /private/var/folders/dt/r5s12t392tb5sk181j3gs4zw0000gn/T/RtmpbeCFhk/devtools231b7fa9df2a/lintr/R/object_usage_linter.R:53
  20: findLocalsList(c(list(body), dropMissings(formals)))
  21: body(fun)
  22: get(fun, mode = "function", envir = parent.frame())
  
  testthat results ================================================================
  OK: 138 SKIPPED: 0 FAILED: 1
  1. Error: Package Style (@test-style.r#4) 
  
  Error: testthat unit tests failed
  Execution halted
```

## BWStest (0.2.1)
Maintainer: Steven E. Pav <shabbychef@gmail.com>  
Bug reports: https://github.com/shabbychef/BWStest/issues

0 errors | 0 warnings | 0 notes

## covr (2.2.2)
Maintainer: Jim Hester <james.f.hester@gmail.com>  
Bug reports: https://github.com/jimhester/covr/issues

0 errors | 0 warnings | 0 notes

## devtools (1.12.0)
Maintainer: Hadley Wickham <hadley@rstudio.com>  
Bug reports: https://github.com/hadley/devtools/issues

0 errors | 0 warnings | 0 notes

## functools (0.2.0)
Maintainer: Paul Hendricks <paul.hendricks.2013@owu.edu>  
Bug reports: https://github.com/paulhendricks/functools/issues

0 errors | 0 warnings | 0 notes

## GSED (1.3)
Maintainer: Marie-Karelle Riviere <eldamjh@gmail.com>

0 errors | 0 warnings | 0 notes

## gWidgets2RGtk2 (1.0-5)
Maintainer: John Verzani <jverzani@gmail.com>

1 error  | 0 warnings | 0 notes

```
checking package dependencies ... ERROR
Package required but not available: ‘RGtk2’

See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
manual.
```

## gWidgets2tcltk (1.0-5)
Maintainer: John Verzani <jverzani@gmail.com>

1 error  | 0 warnings | 0 notes

```
checking whether package ‘gWidgets2tcltk’ can be installed ... ERROR
Installation failed.
See ‘/Users/jhester/Dropbox/projects/memoise/revdep/checks/gWidgets2tcltk.Rcheck/00install.out’ for details.
```

## heemod (0.9.0)
Maintainer: Antoine Filipovic-Pierucci <pierucci@gmail.com>  
Bug reports: https://github.com/pierucci/heemod/issues

0 errors | 0 warnings | 0 notes

## icd9 (1.3.1)
Maintainer: Jack O. Wasey <jack@jackwasey.com>  
Bug reports: https://github.com/jackwasey/icd9/issues

0 errors | 0 warnings | 1 note 

```
checking dependencies in R code ... NOTE
Missing or unexported object: ‘devtools::load_data’
```

## opencage (0.1.0)
Maintainer: Maëlle Salmon <maelle.salmon@yahoo.se>  
Bug reports: http://github.com/ropenscilabs/opencage/issues

0 errors | 0 warnings | 0 notes

## OpenML (1.3)
Maintainer: Giuseppe Casalicchio <giuseppe.casalicchio@stat.uni-muenchen.de>  
Bug reports: https://github.com/openml/openml-r/issues

0 errors | 0 warnings | 0 notes

## prcbench (0.7.3)
Maintainer: Takaya Saito <takaya.saito@outlook.com>  
Bug reports: https://github.com/takayasaito/prcbench/issues

0 errors | 0 warnings | 1 note 

```
checking package dependencies ... NOTE
Package suggested but not available for checking: ‘PerfMeas’
```

## regioneR (1.6.2)
Maintainer: Bernat Gel <bgel@imppc.org>

0 errors | 1 warning  | 4 notes

```
checking whether package ‘regioneR’ can be installed ... WARNING
Found the following significant warnings:
  Warning: package ‘S4Vectors’ was built under R version 3.3.3
  Warning: package ‘IRanges’ was built under R version 3.3.3
See ‘/Users/jhester/Dropbox/projects/memoise/revdep/checks/regioneR.Rcheck/00install.out’ for details.

checking DESCRIPTION meta-information ... NOTE
Packages listed in more than one of Depends, Imports, Suggests, Enhances:
  ‘memoise’ ‘GenomicRanges’ ‘BSgenome’ ‘rtracklayer’ ‘parallel’
A package should be listed in only one of these fields.

checking S3 generic/method consistency ... NOTE
Found the following apparent S3 methods exported but not registered:
  print.permTestResults
See section ‘Registering S3 methods’ in the ‘Writing R Extensions’
manual.

checking R code for possible problems ... NOTE
commonRegions: no visible global function definition for ‘hasArg’
  (/Users/jhester/Dropbox/projects/memoise/revdep/checks/regioneR.Rcheck/00_pkg_src/regioneR/R/commonRegions.R:38)
commonRegions: no visible global function definition for ‘hasArg’
  (/Users/jhester/Dropbox/projects/memoise/revdep/checks/regioneR.Rcheck/00_pkg_src/regioneR/R/commonRegions.R:39)
createFunctionsList: no visible global function definition for ‘hasArg’
  (/Users/jhester/Dropbox/projects/memoise/revdep/checks/regioneR.Rcheck/00_pkg_src/regioneR/R/createFunctionsList.R:47)
createFunctionsList: no visible global function definition for ‘hasArg’
  (/Users/jhester/Dropbox/projects/memoise/revdep/checks/regioneR.Rcheck/00_pkg_src/regioneR/R/createFunctionsList.R:48)
createFunctionsList: no visible global function definition for ‘hasArg’
... 109 lines ...
uniqueRegions: no visible global function definition for ‘hasArg’
  (/Users/jhester/Dropbox/projects/memoise/revdep/checks/regioneR.Rcheck/00_pkg_src/regioneR/R/uniqueRegions.R:37)
uniqueRegions: no visible global function definition for ‘hasArg’
  (/Users/jhester/Dropbox/projects/memoise/revdep/checks/regioneR.Rcheck/00_pkg_src/regioneR/R/uniqueRegions.R:38)
Undefined global functions or variables:
  hasArg is queryHits read.csv read.delim subjectHits
Consider adding
  importFrom("methods", "hasArg", "is")
  importFrom("utils", "read.csv", "read.delim")
to your NAMESPACE file (and ensure that your DESCRIPTION Imports field
contains 'methods').

checking Rd line widths ... NOTE
Rd file 'circularRandomizeRegions.Rd':
  \usage lines wider than 90 characters:
     circularRandomizeRegions(A, genome="hg19", mask=NULL, max.mask.overlap=NULL, max.retries=10, verbose=TRUE, ...)

Rd file 'commonRegions.Rd':
  \examples lines wider than 100 characters:
     plotRegions(list(A, B, commons), chromosome="chr1", regions.labels=c("A", "B", "common"), regions.colors=3:1)

Rd file 'createFunctionsList.Rd':
... 95 lines ...
     plotRegions(list(A, B, splits), chromosome=1, regions.labels=c("A", "B", "splits"), regions.colors=3:1)

Rd file 'subtractRegions.Rd':
  \examples lines wider than 100 characters:
     plotRegions(list(A, B, subtract), chromosome=1, regions.labels=c("A", "B", "subtract"), regions.colors=3:1)

Rd file 'uniqueRegions.Rd':
  \examples lines wider than 100 characters:
     plotRegions(list(A, B, uniques), chromosome="chr1", regions.labels=c("A", "B", "uniques"), regions.colors=3:1)

These lines will be truncated in the PDF manual.
```

## rgho (1.0.1)
Maintainer: Antoine Filipovic-Pierucci <pierucci@gmail.com>  
Bug reports: https://github.com/pierucci/rgho/issues

0 errors | 0 warnings | 0 notes

## RSQLite (1.1-2)
Maintainer: Kirill Müller <krlmlr+r@mailbox.org>  
Bug reports: https://github.com/rstats-db/RSQLite/issues

0 errors | 0 warnings | 0 notes

## saeRobust (0.1.0)
Maintainer: Sebastian Warnholz <Sebastian.Warnholz@fu-berlin.de>  
Bug reports: https://github.com/wahani/saeRobust/issues

0 errors | 0 warnings | 0 notes

## SamplingStrata (1.1)
Maintainer: Giulio Barcaroli <barcarol@istat.it>

0 errors | 0 warnings | 0 notes

## SIDES (1.10)
Maintainer: Marie-Karelle Riviere <eldamjh@gmail.com>

0 errors | 0 warnings | 0 notes

## surveillance (1.13.0)
Maintainer: Sebastian Meyer <seb.meyer@fau.de>  
Bug reports: https://r-forge.r-project.org/tracker/?group_id=45

0 errors | 0 warnings | 2 notes

```
checking package dependencies ... NOTE
Package suggested but not available for checking: ‘INLA’

checking installed package size ... NOTE
  installed size is  9.6Mb
  sub-directories of 1Mb or more:
    R     4.2Mb
    doc   2.3Mb
```

## toaster (0.5.5)
Maintainer: Gregory Kanevsky <gregory.kanevsky@teradata.com>  
Bug reports: https://github.com/teradata-aster-field/toaster/issues

0 errors | 0 warnings | 0 notes

