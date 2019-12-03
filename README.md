# Modification to software MONSTER

## Github
Repository: https://github.com/stef-mueller/MONSTER.git   
get code:
```{bash}
git clone https://github.com/stef-mueller/MONSTER.git
```

## Objective: 
Modify MONSTER for better usage in own research questions

## Source:
Publikation: [10.1002/gepi.21775](https://doi.org/10.1002/gepi.21775)   
Code: [hosted at university of chicago](www.stat.uchicago.edu/~mcpeek/software/index.html)   

## Modifications:
* increased maximum number of individuals: 10,000 -> 40,000
* increased maximum coverage: 100 -> 1000
* increased maximum SNP length: 200 -> 500

## compile modified executable locally

### Requisite
gpl needs to be installed

### Code
```{bash}
make
```

Executable called "myMONSTER" will be compiled in base directory.
