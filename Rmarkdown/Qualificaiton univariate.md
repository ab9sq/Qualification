Quallification of R
========================================================
Explorations Using NIST datasets
-------------------------------------------------------
32-Bit R and 32-bit Windows System 7
-------------------------------------------------------

### Univariate Summary Statistics


```r
options(digits=15)
```

#### Using [NumAcc4.dat](http://www.itl.nist.gov/div898/strd/univ/numacc4.html) file.
The data file was modified to remove the header information that was included and
will be loaded as NumAcc4.txt

The data set has 1 variable and 1001 observations.

First variable 10000000.2 presented as a sample.

expected results (certified) are:

mean = 10000000.2 (exact) 

Standard Deviation = 0.1 (exact)


```r
# load NumAcc4.dat file
# Note: header information was removed from the file and it was renamed NumAcc4.txt

NumAcc4 <- read.table(file="~/R/workspace/qual/raw data/NumAcc4.txt")
mean(NumAcc4$V1)
```

```
## [1] 10000000.2
```

```r
sd(NumAcc4$V1)
```

```
## [1] 0.100000000558794
```

```r
length(NumAcc4$V1)
```

```
## [1] 1001
```


#### Using [NumAcc3.dat](http://www.itl.nist.gov/div898/strd/univ/numacc3.html) file
The data file was modified to remove the header information that was included and
will be loaded as NumAcc3.txt

The data set has 1 variable and 1001 observations.

First variable 1000000.2 presented as a sample.

expected results (certified) are:

mean = 1000000.2 (exact) 

Standard Deviation = 0.1 (exact)

```r
# load NumAcc3.dat, modifided as NumAcc4
NumAcc3 <- read.table(file="~/r/workspace/qual/raw data/numacc3.txt")
mean(NumAcc3$V1)
```

```
## [1] 1000000.2
```

```r
sd(NumAcc3$V1)
```

```
## [1] 0.100000000034925
```

```r
length(NumAcc3$V1)
```

```
## [1] 1001
```


#### Using [NumAcc2.dat](http://www.itl.nist.gov/div898/strd/univ/numacc2.html) file
The data file was modified to remove the header information that was included and
will be loaded as NumAcc2.txt

The data set has 1 variable and 1001 observations.

First variable 1.2 presented as a sample.

expected results (certified) are:

mean = 1.2 (exact) 

Standard Deviation = 0.1 (exact)

```r
# load NumAcc2.dat, modifided as NumAcc4
NumAcc2 <- read.table(file="~/r/workspace/qual/raw data/numacc2.txt")
mean(NumAcc2$V1)
```

```
## [1] 1.2
```

```r
sd(NumAcc2$V1)
```

```
## [1] 0.1
```

```r
length(NumAcc2$V1)
```

```
## [1] 1001
```


#### Using [NumAcc1.dat](http://www.itl.nist.gov/div898/strd/univ/numacc1.html) file
The data file was modified to remove the header information that was included and
will be loaded as NumAcc1.txt

The data set has 1 variable and 3 observations.

First variable 10000001 presented as a sample.

expected results (certified) are:

mean = 10000002 (exact) 

Standard Deviation = 1 (exact)

```r
# load NumAcc1.dat, modifided as NumAcc4
NumAcc1 <- read.table(file="~/r/workspace/qual/raw data/numacc1.txt")
mean(NumAcc1$V1)
```

```
## [1] 10000002
```

```r
sd(NumAcc1$V1)
```

```
## [1] 1
```

```r
length(NumAcc1$V1)
```

```
## [1] 3
```


#### Using [Michelso.dat](http://www.itl.nist.gov/div898/strd/univ/michelso.html) file
The data file was modified to remove the header information that was included and
will be loaded as Michelso.txt

The data set has 1 variable and 100 observations.

First variable 299.85 presented as a sample.

expected results (certified) are:

mean = 299.852400000000

Standard Deviation = 0.0790105478190518

```r
# load Michelso.dat, modifided as NumAcc4
Michelso <- read.table(file="~/r/workspace/qual/raw data/Michelso.txt")
mean(Michelso$V1)
```

```
## [1] 299.8524
```

```r
sd(Michelso$V1)
```

```
## [1] 0.0790105478190507
```

```r
length(Michelso$V1)
```

```
## [1] 100
```

#### Using [Mavro.dat](http://www.itl.nist.gov/div898/strd/univ/mavvo.html) file
The data file was modified to remove the header information that was included and
will be loaded as Mavro.txt

The data set has 1 variable and 50 observations.

First variable 2.00180 presented as a sample.

expected results (certified) are:

mean = 2.00185600000000

Standard Deviation = 0.000429123454003053

```r
# load Mavro.dat, modifided as NumAcc4
Mavro <- read.table(file="~/r/workspace/qual/raw data/Mavro.txt")
mean(Mavro$V1)
```

```
## [1] 2.001856
```

```r
sd(Mavro$V1)
```

```
## [1] 0.000429123454003085
```

```r
length(Mavro$V1)
```

```
## [1] 50
```

#### Using [Lew.dat](http://www.itl.nist.gov/div898/strd/univ/lew.html) file
The data file was modified to remove the header information that was included and
will be loaded as Mavro.txt

The data set has 1 variable and 200 observations.

First variable -213 presented as a sample.

expected results (certified) are:

mean = -177.435000000000

Standard Deviation = 277.332168044316

```r
# load Lew.dat, modifided as NumAcc4
Lew <- read.table(file="~/r/workspace/qual/raw data/Lew.txt")
mean(Lew$V1)
```

```
## [1] -177.435
```

```r
sd(Lew$V1)
```

```
## [1] 277.332168044316
```

```r
length(Lew$V1)
```

```
## [1] 200
```

#### Using [Lottery.dat](http://www.itl.nist.gov/div898/strd/univ/lottery.html) file
The data file was modified to remove the header information that was included and
will be loaded as Mavro.txt

The data set has 1 variable and 218 observations.

First variable 162 presented as a sample.

expected results (certified) are:

mean = 518.958715596330

Standard Deviation = 291.699727470969 


```r
# load Lottery.dat, modifided as NumAcc4
Lottery <- read.table(file="~/r/workspace/qual/raw data/Lottery.txt")
mean(Lottery$V1)
```

```
## [1] 518.95871559633
```

```r
sd(Lottery$V1)
```

```
## [1] 291.699727470969
```

```r
length(Lottery$V1)
```

```
## [1] 218
```

#### Using [PiDigits.dat](http://www.itl.nist.gov/div898/strd/univ/pidigits.html) file
The data file was modified to remove the header information that was included and
will be loaded as Mavro.txt

The data set has 1 variable and 5000 observations.

Variables are all single digits.

expected results (certified) are:

mean = 4.53480000000000 

Standard Deviation = 2.86733906028871 
 


```r
# load PhiDigits.dat, modifided as NumAcc4
PiDigits <- read.table(file="~/r/workspace/qual/raw data/PiDigits.txt")
mean(PiDigits$V1)
```

```
## [1] 4.5348
```

```r
sd(PiDigits$V1)
```

```
## [1] 2.86733906028871
```

```r
length(PiDigits$V1)
```

```
## [1] 5000
```

