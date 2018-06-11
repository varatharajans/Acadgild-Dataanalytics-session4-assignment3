# Acadgild-Dataanalytics-session4-assignment3
DATA ANALYTICS WITH R, EXCEL AND TABLEAU SESSION 4ASSIGNMENT 3
assignment 4.3
varatharajan
June 11, 2018
library(readxl)
usarrests <- read_excel("C:/R_practice/usarrests.xls")
View(usarrests)
states<-rownames(USArrests)
print(states)
grep(pattern = "W", x = states, value = TRUE)
grep(pattern = "w", x = states, value = TRUE)
hist(nchar(states), main = "Histogram", xlab = "number of characters in US State names")



[1] "Alabama"        "Alaska"         "Arizona"        "Arkansas"      
 [5] "California"     "Colorado"       "Connecticut"    "Delaware"      
 [9] "Florida"        "Georgia"        "Hawaii"         "Idaho"         
[13] "Illinois"       "Indiana"        "Iowa"           "Kansas"        
[17] "Kentucky"       "Louisiana"      "Maine"          "Maryland"      
[21] "Massachusetts"  "Michigan"       "Minnesota"      "Mississippi"   
[25] "Missouri"       "Montana"        "Nebraska"       "Nevada"        
[29] "New Hampshire"  "New Jersey"     "New Mexico"     "New York"      
[33] "North Carolina" "North Dakota"   "Ohio"           "Oklahoma"      
[37] "Oregon"         "Pennsylvania"   "Rhode Island"   "South Carolina"
[41] "South Dakota"   "Tennessee"      "Texas"          "Utah"          
[45] "Vermont"        "Virginia"       "Washington"     "West Virginia" 
[49] "Wisconsin"      "Wyoming"       
[1] "Washington"    "West Virginia" "Wisconsin"     "Wyoming"      
[1] "Delaware"      "Hawaii"        "Iowa"          "New Hampshire"
[5] "New Jersey"    "New Mexico"    "New York"     
R Console


histogram and R markdown for this file is attached as attachment



 


{r setup, include=FALSE} knitr::opts_chunk$set(echo = TRUE)
R Markdown
This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see http://rmarkdown.rstudio.com.
When you click the Knit button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:
{r cars} summary(cars)
Including Plots
You can also embed plots, for example:
{r pressure, echo=FALSE} plot(pressure)
Note that the echo = FALSE parameter was added to the code chunk to prevent printing of the R code that generated the plot.
 
