# RShiny_PlasticityTradeoff

PlasticityTradeoff is an interactive shiny app that allows any user to visualize the relationship between plasticity and thermal tolerance range of organisms across many taxa. The app uses the data colleted by [Calosi (2015)](https://royalsocietypublishing.org/doi/10.1098/rsbl.2007.0408) on beetles and a larger dataset published by [Gunderson & Stillman (2015)](https://royalsocietypublishing.org/doi/full/10.1098/rspb.2015.0401)

## Prerequisites for opening in Rstudio
Git and Rstudio ([Instructions](https://resources.github.com/whitepapers/github-and-rstudio/))  
Installation of the following R packages:
shiny, shinythemes, shinyWidgets, magrittr, plotly, dplyr, cicerone, shinyjs, shinyBS

```
pkgs <- c("shiny", "shinythemes", "shinyWidgets", "magrittr", "plotly", "dplyr", "cicerone", "shinyjs", "shinyBS")
lapply(pkgs, FUN = function(x) {
    if (!require(x, character.only = TRUE)) {
      install.packages(x, dependencies = TRUE)
    }
  }
)
```

## Using PlasticityTradeoff
* Opening in Rstudio:  
Click on "Code" on the top right to copy the link to this repository.  
Click ```File```, ```New Project```, ```Version Control```, ```Git```  
Paste the repository URL and click ```Create Project```.

* Alternatively, go to [this link](https://huckley.shinyapps.io/RShiny_PlasticityTradeoff/).

We have a google doc with questions to guide through the app for further understanding of the topic.

## Contributing to PlasticityTradeoff
<!--- If your README is long or you have some specific process or steps you want contributors to follow, consider creating a separate CONTRIBUTING.md file--->
To contribute to PlasticityTradeoff, follow these steps:

1. Fork this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create the pull request.

Alternatively see the GitHub documentation on [creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).
