# intro-R
Knowing a little bit about our awesome friend R

## First steps
- [Download R](https://cran.itam.mx/)
- [Download RStudio](https://www.rstudio.com/products/rstudio/download/#download)
- [Clone this repository (with submodules)](https://www.rstudio.com/products/rstudio/download/#download):

  `git clone --recurse-submodules https://github.com/adfmb/intro-R.git`
  
  - Or Fork it and then clone it from your user 
  
  `git clone --recurse-submodules https://github.com/<youruser>/intro-R.git`
  

## Add as `remote` the repo adfmb/intro-R
- Go to the repository's folder on your computer
 `cd intro-R`
- Check with the `git remote -v`
```
➜ git remote -v
origin  https://github.com/<youruser>/intro-R.git (fetch)
origin  https://github.com/<youruser>/intro-R.git (push)
```
- Add the repo-class from url for the future *pulls*:
  
  `git remote add repo-class https://github.com/adfmb/intro-R.git`
- Check again with the `git remote -v`
```
➜ git remote -v
origin  https://github.com/<youruser>/intro-R.git (fetch)
origin  https://github.com/<youruser>/intro-R.git (push)
repo-class     https://github.com/adfmb/intro-R.git (fetch)
repo-class      https://github.com/adfmb/intro-R.git (push)
```

## Your own working directory
- Standing at *intro-R/*, create a folder with your name where you will be saving your progress
 `mkdir <yourname>`







## References
- [Intro *by rstudio*](https://github.com/rstudio/Intro)
- [courses-intro-to-r *by datacamp*](https://github.com/datacamp/courses-intro-to-r)
- [IntroToDataScience *by EasyD*](https://github.com/EasyD/IntroToDataScience)
- [git tour at **tutoriales/** *by ITAM-DS* ](https://github.com/ITAM-DS/tutoriales/blob/master/2-git-tour.Rmd)
