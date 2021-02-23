# memos


![gitleaks](https://github.com/NOAA-EDAB/memos/workflows/gitleaks/badge.svg)

Use this repository to write memos developed in R or other plain text languages. 

**Note**: The following guidelines are based on a memo built using the package `linl`.

### Rmarkdown
Developing a memo in Rmarkdown is a relatively painless process *if* you are relying on an existing codebase for your project. A useful resource for producing Rmarkdown letters can be found [here](http://dirk.eddelbuettel.com/code/linl.html), which gives an overview of writing letters with Rmarkdown to produce pdf output. 

An ExampleMemo.Rmd is in the root directory. NEFSC letterhead is supplied in the letterhead folder.

### Directory structure & naming scheme
Why is naming files so difficult? To ameliorate your anxiety, please use the following directory structure and naming scheme for your memo (numbers indicate outer->inner directory order):

#### Directory Structure
1.  Name of project (e.g. `State of the Ecosystem`)
2.  Create a subfolder for each letter with the title and date (e.g. `NEFMC YYYY-MM-DD`). Copy the letterhead folder into your subfolder if you want the NEFSC letterhead, or supply your own 
3.  All associated subdirectories and a .Rproj file may be stored here. For example, a folder where R scripts are kept should be called `R`, and this should be on the same level as your .Rproj file. 

#### Memo naming scheme
Memo filenames should follow the format of `YYYYMMDD_topic_surname`.



*This repository is a scientific product and is not official communication of the National Oceanic and Atmospheric Administration, or the United States Department of Commerce. All NOAA GitHub project code is provided on an ‘as is’ basis and the user assumes responsibility for its use. Any claims against the Department of Commerce or Department of Commerce bureaus stemming from the use of this GitHub project will be governed by all applicable Federal law. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by the Department of Commerce. The Department of Commerce seal and logo, or the seal and logo of a DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by DOC or the United States Government.*
