## Getting Started

### Download R
Click on the link to go to R's homepage. <https://www.r-project.org/>

![R project home](r_homepage_screenshot.png)

To download R:

1. Click the **download R** link under Getting Started.
2. Select your CRAN mirror. Click one of the links at the top under 0-Cloud.
3. Click on the link that says "Download R for [Your Operating System]"
4. What to Pick
    - For Mac, select the latest release
    - For Windows, select base
5. R should be downloaded to your computer and you should follow the normal steps to install

### Download RStudio

Click on the link to go to R's homepage. <https://www.rstudio.com/>

![RStudio homepage](rstudio_homepage_screenshot.png)

To download RStudio:

1. Click the Download link underneath the RStudio cartoon.
2. Click the DOWNLOAD button for the FREE RStudio Desktop.
3. Select your operating system from the list.
4. The file should download to your computer and then you can install it like any other program.

### Install Packages
To install the main packages that will be required for meetups, open RStudio and copy and paste the code below into the **Console**.

```r
install.packages('tidyverse', 'viridis')
```
If that doesn't work, copy and paste this code.

```r
packages <- ('dplyr', 'forcats', 'ggplot2', 'purrr', 'readr', 'stringr', 'tibble', 'tidyr', 'viridis')
install.packages(packages)
```

# Content
### Week 1 (Sep 7)

Outline

- What's a meetup? / What's changing with meetups? [(slides)](week1/bioinformatics_meetup_introduction_2018.09.07.pdf)
- Getting Started (see section above)
- [Introduction to Rmarkdown](week1/intro_to_rmarkdown.Rmd)

Practice for the week is [here](week1/week1_intro_to_rmarkdown_practice.Rmd) and answers are [here in R markdown](week1/week1_intro_to_rmarkdown_practice_ANSWERKEY.Rmd) and [in html](week1/week1_intro_to_rmarkdown_practice_ANSWERKEY.html)

---

### Week 2 (Sep 14)


<br><br>
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
