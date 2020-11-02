Through this process:

DESCRIPTION is used to edit the DESCRIPTION
DATASET.R needs to be copied into the file in data-raw 
pdga-approved-disc-golf-discs_2020-10-04T15-02-04.csv needs to be copied to data-raw
DiscGolf.R needs to be copied into the R folder

0. Please refer to the files in the DiscGolf_files folder within the week10 folder.  Also please be sure that you've installed a personal access token!

1. create a new project (new package with devtools)

2. edit the DESCRIPTION with your information (see the DESCRIPTION file I've provided for an example)

3. run:

  `options(use_this.fullname = "Nicholas Horton")`

  `usethis::use_mit_license()`

4. `usethis::use_data_raw()` to create the `data-raw` folder

5. open the data-raw folder and DATASET.R then replace with contents of wrangling commands from the DATASET.R file I've provided

6. change working directory to source file location, then "source DATASET.R"

7. check that the data folder now has the data

8. copy DiscGolf.R (documentation that I've provided) to the R folder

9. `usethis::use_readme_rmd()` to create a `README.Rmd` file

10. knit the file to create `README.md`

11. commit files

12. usethis::use_git() to add files

13. usethis::use_github() to connect this project to GitHub.

14. check package by clicking on "check package" in the "Build" tab.

15. click on the "build and install" button in the "Build" tab.

16. Type "DiscGolf" at the console to confirm that things are working.

17. Check that you can also install the package using `remotes::install_github("YOURGITHUBNAME/DiscGolf")`


Next step?  Create your own data package using the data you curated for `hw6`.

