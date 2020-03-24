# 02-compiling-advanced-r-xuexuan934243339
02-compiling-advanced-r-xuexuan934243339 created by GitHub Classroom
Problems and Solutions to Build the Book Advanced R Programming using RStudio
xuexuan

Quitting from lines 223-235 (Introduciton.Rmd)
Adding encoding = "UTF-8" in line 224 can fix it. The line 224 is displayed as contributors <- read.csv("contributors.csv", stringsAsFactors = FALSE,encoding = "UTF-8")

Quitting from lines 327-328 (Names-values.Rmd)
I first updated rlang by the update function in RStudio, but it failed. So I manually removed rlang based
on the path D:/R/R-3.6.1/library/rlang, and then reinstalled rlang using install.packages("rlang")

“xelatex” not Found
According to the reference TinyTex(The lowercase tinytex means the R package, and the camel-case TinyTeX
means the LaTeX distribution). Use tinytex to install TinyTex might fix the problem, but I still got other
problems. In the end, I used MiKTeX instead. Be careful, choose “Always install missing packages on-the-fly”
when MiKTeX let you choose whether missing packages are to be installed.



