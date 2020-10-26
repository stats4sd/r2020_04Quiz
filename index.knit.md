---
title: "Using RStudio / Importing data: Quiz & Exercises"
output: 
  learnr::tutorial:
    progressive: true
    allow_skip: true
    df_print: paged
runtime: shiny_prerendered
description: >
  Learn how to use RStudio and import data - Quiz/Exo.
---



## Quiz

*Question 1*

<!--html_preserve--><div class="panel panel-default">
<div data-label="Q1" class="tutorial-question panel-body">
<div id="Q1-answer_container" class="shiny-html-output"></div>
<div id="Q1-message_container" class="shiny-html-output"></div>
<div id="Q1-action_button_container" class="shiny-html-output"></div>
<script>if (Tutorial.triggerMathJax) Tutorial.triggerMathJax()</script>
</div>
</div><!--/html_preserve-->




<img src="./images/packageQuestion.jpg" width="100%" style="display: block; margin: auto auto auto 0;" />


*Question 2*

<!--html_preserve--><div class="panel panel-default">
<div data-label="Q2" class="tutorial-question panel-body">
<div id="Q2-answer_container" class="shiny-html-output"></div>
<div id="Q2-message_container" class="shiny-html-output"></div>
<div id="Q2-action_button_container" class="shiny-html-output"></div>
<script>if (Tutorial.triggerMathJax) Tutorial.triggerMathJax()</script>
</div>
</div><!--/html_preserve-->




<img src="./images/Quiz1.PNG" width="100%" style="display: block; margin: auto auto auto 0;" />


*Question 3*

<!--html_preserve--><div class="panel panel-default">
<div data-label="Q3" class="tutorial-question panel-body">
<div id="Q3-answer_container" class="shiny-html-output"></div>
<div id="Q3-message_container" class="shiny-html-output"></div>
<div id="Q3-action_button_container" class="shiny-html-output"></div>
<script>if (Tutorial.triggerMathJax) Tutorial.triggerMathJax()</script>
</div>
</div><!--/html_preserve-->


*Question 4*

<!--html_preserve--><div class="panel panel-default">
<div data-label="Q4" class="tutorial-question panel-body">
<div id="Q4-answer_container" class="shiny-html-output"></div>
<div id="Q4-message_container" class="shiny-html-output"></div>
<div id="Q4-action_button_container" class="shiny-html-output"></div>
<script>if (Tutorial.triggerMathJax) Tutorial.triggerMathJax()</script>
</div>
</div><!--/html_preserve-->




## Exercises


**Exercise 1: Now that you have imported the Happiness dataset into R – let’s do a quick exercise to recap what we learnt in Modules 1-3, but writing out the code entirely in RStudio instead of online.**

1.	Find the 5 countries with the lowest ‘generosity scores’  
2.	Produce a subset of countries which have below average scores for both GDP and generosity.  
3.	Make a plot showing the relationship between generosity and GDP per capita  
 

**Exercise 2: Download the file below that contains the imdb dataset and the solutions for the module 3 exercises. Save these in your project folder. Import the data using RStudio menu and go through the R Markdown file to reproduce the solution in your own machine**

[Module-3-Data-and-Solutions.zip](https://github.com/stats4sd/r2020_04Quiz/raw/main/Module-3-Data-and-Solutions.zip)



## Appendix: 'Happiness' dataset 

The data used for the questions in this workbook comes from the World Happiness Report 2019. The World Happiness Report is an annual publication of the United Nations Sustainable Development Solutions Network. It aims at ranking 156 countries by level of global happiness of their population, by doing an annual survey on their citizens.

In this dataset, the variables 'GDP per capita','Social support','Healthy life expectancy','Freedom to make life choices','Generosity' and 'Perceptions of corruption' are factors used to compute the Happiness Score ('Score').

The methodology, as well as more information about this publication, can be found <a href="https://worldhappiness.report/ed/2019/" target="_blank">here </a>. 


## Appendix: 'imdb' dataset

For one exercise of this module, we are using a dataset called "imdb", which we constructed from the subsets of the Internet Movie Database made available for non-commercial purposes by the IMDb team:
<a href="https://www.imdb.com/interfaces/" target="_blank">https://www.imdb.com/interfaces/</a>


It contains the following information for all the entries having more than 500 votes, that are not of type "tvEpisodes" and for which information about year of release, running time and director(s) was available at the time of extraction (28/09/2020):  



|Column        |Description                                                                                          |
|:-------------|:----------------------------------------------------------------------------------------------------|
|title         |popular title of the entry                                                                           |
|type          |type of entry: movie, short, tvMiniSeries, tvMovie, tvSeries, tvShort, tvSpecial, video or videoGame |
|year          |year of release (for series, year of release of the first episode)                                   |
|length        |duration in minutes                                                                                  |
|numVotes      |number of votes for the entry                                                                        |
|averageRating |IMDb's weighted average rating for the entry                                                         |
|director      |director of the entry (if multiple directors, the first one was picked)                              |
|birthYear     |year of birth of the director                                                                        |
|animation     |the entry is of genre animation (TRUE/FALSE)                                                         |
|action        |the entry is of genre action (TRUE/FALSE)                                                            |
|adventure     |the entry is of genre adventure (TRUE/FALSE)                                                         |
|comedy        |the entry is of genre comedy (TRUE/FALSE)                                                            |
|documentary   |the entry is of genre documentary (TRUE/FALSE)                                                       |
|fantasy       |the entry is of genre fantasy (TRUE/FALSE)                                                           |
|romance       |the entry is of genre romance (TRUE/FALSE)                                                           |
|sci_fi        |the entry is of genre science fiction (TRUE/FALSE)                                                   |
|thriller      |the entry is of genre thriller (TRUE/FALSE)                                                          |




## Appendix:  Useful reference links  

RStudio website:<a href="https://rstudio.com/" target="_blank">https://rstudio.com/   </a> 

R-project website:<a href="https://www.r-project.org/" target="_blank">https://www.r-project.org/   </a> 

Andy Field's Getting started in R and RStudio:<a href="http://milton-the-cat.rocks/learnr/r/r_getting_started" target="_blank">http://milton-the-cat.rocks/learnr/r/r_getting_started   </a> 

R Markdown documentation:<a href="https://rmarkdown.rstudio.com/lesson-1.html" target="_blank">https://rmarkdown.rstudio.com/lesson-1.html   </a> 

RStudio CheatSheet:<a href="https://rstudio.com/wp-content/uploads/2016/01/rstudio-IDE-cheatsheet.pdf" target="_blank">https://rstudio.com/wp-content/uploads/2016/01/rstudio-IDE-cheatsheet.pdf   </a>

R Markdown CheatSheet:<a href="https://rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf" target="_blank">https://rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf   </a>


Illustrated presentation of 'tidy data': <a href="https://docs.google.com/presentation/d/1N7hKepabvl9OrHjvGJWPjUsfzVdB5xzV5AsFndgSwms/edit?usp=sharing" target="_blank">Make friends with tidy data </a> 

Video explaining the command to import text files into R - DataCamp:<a href="https://www.youtube.com/watch?v=Yy-ismDUkkQ" target="_blank">https://www.youtube.com/watch?v=Yy-ismDUkkQ   </a> 

Article on the RStudio support site showing how to import data from different files via the RStudio import menu:<a href="https://support.rstudio.com/hc/en-us/articles/218611977-Importing-Data-with-RStudio" target="_blank">Importing Data with RStudio</a> 

RStudio documentation on connecting to databases using R  <a href="https://db.rstudio.com" target="_blank">https://db.rstudio.com </a>


<!--html_preserve-->
<script type="application/shiny-prerendered" data-context="server-start">
library(learnr)
library(dplyr)
knitr::opts_chunk$set(echo = FALSE)
</script>
<!--/html_preserve-->
<!--html_preserve-->
<script type="application/shiny-prerendered" data-context="server">
learnr:::register_http_handlers(session, metadata = NULL)
</script>
<!--/html_preserve-->
<!--html_preserve-->
<script type="application/shiny-prerendered" data-context="server">
session$onSessionEnded(function() {
        learnr:::session_stop_event(session)
      })
</script>
<!--/html_preserve-->
<!--html_preserve-->
<script type="application/shiny-prerendered" data-context="server">
learnr:::question_prerendered_chunk(structure(list(type = "learnr_radio", label = "Q1", question = structure("Which of these statements is true?", html = TRUE, class = c("html", "character")), answers = list(structure(list(id = "lnr_ans_6ec9213",     option = "RStudio is useless without R", value = "RStudio is useless without R",     label = structure("RStudio is useless without R", html = TRUE, class = c("html",     "character")), correct = TRUE, message = NULL), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_2125757",     option = "R is a powerful Interactive Development Environment",     value = "R is a powerful Interactive Development Environment",     label = structure("R is a powerful Interactive Development Environment", html = TRUE, class = c("html",     "character")), correct = FALSE, message = structure("No, RStudio is the IDE", html = TRUE, class = c("html",     "character"))), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_ebc36f6", option = "Without RStudio, you cannot use R",     value = "Without RStudio, you cannot use R", label = structure("Without RStudio, you cannot use R", html = TRUE, class = c("html",     "character")), correct = FALSE, message = structure("R can work very well without RStudio. It&#39;s just not that user friendly", html = TRUE, class = c("html",     "character"))), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_b6ed2ad", option = "You need to install RStudio first, then you can install R",     value = "You need to install RStudio first, then you can install R",     label = structure("You need to install RStudio first, then you can install R", html = TRUE, class = c("html",     "character")), correct = FALSE, message = structure("No, you should start by installing R", html = TRUE, class = c("html",     "character"))), class = c("tutorial_question_answer", "tutorial_quiz_answer"))), button_labels = list(submit = structure("Submit Answer", html = TRUE, class = c("html", "character")), try_again = structure("Try Again", html = TRUE, class = c("html", "character"))), messages = list(correct = structure("Correct!", html = TRUE, class = c("html", "character")), try_again = structure("Incorrect", html = TRUE, class = c("html", "character")), incorrect = structure("Incorrect", html = TRUE, class = c("html", "character")), message = NULL, post_message = NULL), ids = list(    answer = "Q1-answer", question = "Q1"), loading = structure("<strong>Loading:<\u002fstrong> \nWhich of these statements is true?\n<br/><br/><br/>", html = TRUE, class = c("html", "character")), random_answer_order = TRUE, allow_retry = TRUE,     seed = 1736299475.19147, options = list()), class = c("learnr_radio", "tutorial_question")))
</script>
<!--/html_preserve-->
<!--html_preserve-->
<script type="application/shiny-prerendered" data-context="server">
learnr:::question_prerendered_chunk(structure(list(type = "learnr_radio", label = "Q2", question = structure("Why is R giving an error in the above screenshot?", html = TRUE, class = c("html", "character")), answers = list(structure(list(id = "lnr_ans_200087d",     option = "The command for reading the data is missing", value = "The command for reading the data is missing",     label = structure("The command for reading the data is missing", html = TRUE, class = c("html",     "character")), correct = FALSE, message = structure("No, it is present at the top of the file: Pulse &lt;- read.csv(&#39;Pulse.csv&#39;)", html = TRUE, class = c("html",     "character"))), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_612c9d4", option = "The command library(ggplot2) is missing",     value = "The command library(ggplot2) is missing", label = structure("The command library(ggplot2) is missing", html = TRUE, class = c("html",     "character")), correct = FALSE, message = structure("It is missing, but we don&#39;t need it, since we are not plotting anything", html = TRUE, class = c("html",     "character"))), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_7d54dce", option = "We did not specify the name of our summary statistic",     value = "We did not specify the name of our summary statistic",     label = structure("We did not specify the name of our summary statistic", html = TRUE, class = c("html",     "character")), correct = FALSE, message = structure("It&#39;s good practice to name our summary statistics indeed, but ommiting the name is not an &#39;error&#39;", html = TRUE, class = c("html",     "character"))), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_bde451c", option = "The column names are incorrect",     value = "The column names are incorrect", label = structure("The column names are incorrect", html = TRUE, class = c("html",     "character")), correct = FALSE, message = structure("No, the column names are correct", html = TRUE, class = c("html",     "character"))), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_dc355f3", option = "Pipes don't work within R chunks",     value = "Pipes don't work within R chunks", label = structure("Pipes don&#39;t work within R chunks", html = TRUE, class = c("html",     "character")), correct = FALSE, message = structure("pipes work very well within R chunks", html = TRUE, class = c("html",     "character"))), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_fb6a4a4", option = "The project file was not created",     value = "The project file was not created", label = structure("The project file was not created", html = TRUE, class = c("html",     "character")), correct = FALSE, message = structure("We can&#39;t tell from this screenshot whether a project file was created or not. We can say that it cannot be responsible for the error though.", html = TRUE, class = c("html",     "character"))), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_6e9413a", option = "The command library(dplyr) is missing",     value = "The command library(dplyr) is missing", label = structure("The command library(dplyr) is missing", html = TRUE, class = c("html",     "character")), correct = TRUE, message = NULL), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_cd0ac14",     option = "The symbol used for the pipe operator is wrong",     value = "The symbol used for the pipe operator is wrong",     label = structure("The symbol used for the pipe operator is wrong", html = TRUE, class = c("html",     "character")), correct = FALSE, message = structure("", html = TRUE, class = c("html",     "character"))), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_3660d4", option = "We are using pipes, but the data argument of each function is missing",     value = "We are using pipes, but the data argument of each function is missing",     label = structure("We are using pipes, but the data argument of each function is missing", html = TRUE, class = c("html",     "character")), correct = FALSE, message = structure("The pipe command is correct. With pipes, we ommit the data argument of the function", html = TRUE, class = c("html",     "character"))), class = c("tutorial_question_answer", "tutorial_quiz_answer"))), button_labels = list(submit = structure("Submit Answer", html = TRUE, class = c("html", "character")), try_again = structure("Try Again", html = TRUE, class = c("html", "character"))), messages = list(correct = structure("Correct!", html = TRUE, class = c("html", "character")), try_again = structure("Incorrect", html = TRUE, class = c("html", "character")), incorrect = structure("Incorrect", html = TRUE, class = c("html", "character")), message = NULL, post_message = NULL), ids = list(    answer = "Q2-answer", question = "Q2"), loading = structure("<strong>Loading:<\u002fstrong> \nWhy is R giving an error in the above screenshot?\n<br/><br/><br/>", html = TRUE, class = c("html", "character")), random_answer_order = TRUE, allow_retry = TRUE,     seed = 1040645799.01541, options = list()), class = c("learnr_radio", "tutorial_question")))
</script>
<!--/html_preserve-->
<!--html_preserve-->
<script type="application/shiny-prerendered" data-context="server">
learnr:::question_prerendered_chunk(structure(list(type = "learnr_radio", label = "Q3", question = structure("The above R Markdown file runs fine, but is missing the point of using R Markdown. Why?", html = TRUE, class = c("html", "character")), answers = list(structure(list(id = "lnr_ans_11213ac",     option = "The comments should be part of the text outside the R chunks. That way, an R Markdown document can become a proper report",     value = "The comments should be part of the text outside the R chunks. That way, an R Markdown document can become a proper report",     label = structure("The comments should be part of the text outside the R chunks. That way, an R Markdown document can become a proper report", html = TRUE, class = c("html",     "character")), correct = TRUE, message = NULL), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_ba93a04",     option = "With R Markdown, all the libraries are already preloaded, so there's no need to have commands that load libraries!",     value = "With R Markdown, all the libraries are already preloaded, so there's no need to have commands that load libraries!",     label = structure("With R Markdown, all the libraries are already preloaded, so there&#39;s no need to have commands that load libraries!", html = TRUE, class = c("html",     "character")), correct = FALSE, message = structure("No, you still need to load libraries in an R Markdown file", html = TRUE, class = c("html",     "character"))), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_598a1ff", option = "R Markdown is made for writing R code. Ideally, we shouldn't have any text or comment in such document, so that it is reproducible",     value = "R Markdown is made for writing R code. Ideally, we shouldn't have any text or comment in such document, so that it is reproducible",     label = structure("R Markdown is made for writing R code. Ideally, we shouldn&#39;t have any text or comment in such document, so that it is reproducible", html = TRUE, class = c("html",     "character")), correct = FALSE, message = structure("No, the advantage of R Markdown is that it is great for writing reproducible reports. So it should contain text", html = TRUE, class = c("html",     "character"))), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_aaee874", option = "The commands should all be included in the same R chunk, so that they can be run altogether. That's the beauty of R Markdown!",     value = "The commands should all be included in the same R chunk, so that they can be run altogether. That's the beauty of R Markdown!",     label = structure("The commands should all be included in the same R chunk, so that they can be run altogether. That&#39;s the beauty of R Markdown!", html = TRUE, class = c("html",     "character")), correct = FALSE, message = structure("No, having all the commands inside one unique R chunk would be missing the point as well.", html = TRUE, class = c("html",     "character"))), class = c("tutorial_question_answer", "tutorial_quiz_answer"))), button_labels = list(submit = structure("Submit Answer", html = TRUE, class = c("html", "character")), try_again = structure("Try Again", html = TRUE, class = c("html", "character"))), messages = list(correct = structure("Correct!", html = TRUE, class = c("html", "character")), try_again = structure("Incorrect", html = TRUE, class = c("html", "character")), incorrect = structure("Incorrect", html = TRUE, class = c("html", "character")), message = NULL, post_message = NULL), ids = list(    answer = "Q3-answer", question = "Q3"), loading = structure("<strong>Loading:<\u002fstrong> \nThe above R Markdown file runs fine, but is missing the point of using R Markdown. Why?\n<br/><br/><br/>", html = TRUE, class = c("html", "character")), random_answer_order = TRUE, allow_retry = TRUE,     seed = 1726033901.69625, options = list()), class = c("learnr_radio", "tutorial_question")))
</script>
<!--/html_preserve-->
<!--html_preserve-->
<script type="application/shiny-prerendered" data-context="server">
learnr:::question_prerendered_chunk(structure(list(type = "learnr_checkbox", label = "Q4", question = structure("What is important for your data if you want to import it into R? (select all that apply)", html = TRUE, class = c("html", "character")), answers = list(structure(list(id = "lnr_ans_cd09511",     option = "It should be made of one single rectangle of data",     value = "It should be made of one single rectangle of data",     label = structure("It should be made of one single rectangle of data", html = TRUE, class = c("html",     "character")), correct = TRUE, message = NULL), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_7b3babb",     option = "The column names should lie in one row only", value = "The column names should lie in one row only",     label = structure("The column names should lie in one row only", html = TRUE, class = c("html",     "character")), correct = TRUE, message = NULL), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_3a749d6",     option = "There shouldn't be any gap between rows or columns",     value = "There shouldn't be any gap between rows or columns",     label = structure("There shouldn&#39;t be any gap between rows or columns", html = TRUE, class = c("html",     "character")), correct = TRUE, message = NULL), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_cf2aaee",     option = "All the columns should have the same length, and the same for the rows",     value = "All the columns should have the same length, and the same for the rows",     label = structure("All the columns should have the same length, and the same for the rows", html = TRUE, class = c("html",     "character")), correct = TRUE, message = NULL), class = c("tutorial_question_answer", "tutorial_quiz_answer")), structure(list(id = "lnr_ans_a3c8d6b",     option = "It shouldn't contain any merged cells", value = "It shouldn't contain any merged cells",     label = structure("It shouldn&#39;t contain any merged cells", html = TRUE, class = c("html",     "character")), correct = TRUE, message = NULL), class = c("tutorial_question_answer", "tutorial_quiz_answer"))), button_labels = list(submit = structure("Submit Answer", html = TRUE, class = c("html", "character")), try_again = structure("Try Again", html = TRUE, class = c("html", "character"))), messages = list(correct = structure("Correct!", html = TRUE, class = c("html", "character")), try_again = structure("Incorrect", html = TRUE, class = c("html", "character")), incorrect = structure("Incorrect", html = TRUE, class = c("html", "character")), message = NULL, post_message = NULL), ids = list(    answer = "Q4-answer", question = "Q4"), loading = structure("<strong>Loading:<\u002fstrong> \nWhat is important for your data if you want to import it into R? (select all that apply)\n<br/><br/><br/>", html = TRUE, class = c("html", "character")), random_answer_order = TRUE, allow_retry = TRUE,     seed = 36568393.9829715, options = list()), class = c("learnr_checkbox", "tutorial_question")))
</script>
<!--/html_preserve-->
