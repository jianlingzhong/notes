
## Warning: unable to access index for repository
If run into the following error when trying to install a package:

```Bash
Warning: unable to access index for repository https://cran.rstudio.com/src/contrib
```

Most likely it's due to the url not set properly. Use the following instead:

```R
install.packages('RJDBC', contriburl='http://cran.rstudio.com/src/contrib/')
```


