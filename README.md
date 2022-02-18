# data repo for collaborative working

This is a github repo so we can work collaboratively and so you guys can learn (if you don't already know) version control which is really useful for science (in my opinion). I will expand on this later but it's late as I'm writing this.

Feel free to fork the repo and/or clone it locally if you like (see here https://docs.github.com/en/get-started/quickstart/fork-a-repo) - then you can manage the files independently. You can also, from this repo or your own fork, load files directly into R via: 
```
install.packages('RCurl')
library(RCurl)
x <- getURL("https://raw.githubusercontent.com/blex-max/msc_2022/main/OTU_table.csv") # or environment.csv etc.
y <- read.csv(text = x)
```


## file descriptions

The OTU_table.csv contains a matrix of raw abundances of ectos, rows are sites, columns are species hypothesis from UNITE 7.

environmental.csv is a collated dataframe of all environmental variables averaged across measured years for each site.

sites_with_biogeography.csv gives you a little more info about the sites, you may or may not need it.  
