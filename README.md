# AN588_Zombies_martah
Homework for Week 4

##Instruction

Create a new GitHub repo and git-referenced Rstudio Project called “AN588_Zombies_BUlogin”. Within that repo, create a new .Rmd file called “BUlogin_OriginalHomeworkCode_03”. Modules 03-08 will each have concepts and example code that will help you complete this assignment. Don’t forget to add your Peer Group and instructor as collaborators, and to accept their invitations to you. Making sure to push both the markdown and knitted .html files to your repository, do the following:

Load in the dataset “zombies.csv” from my GitHub repo. This data includes the first name, last name, and gender of the entire population of 1000 people who have survived the zombie apocalypse and are now ekeing out an existence somewhere on the East Coast, along with several other variables (height, weight, age, number of years of education, number of zombies they have killed, and college major; see here for info on important post-zombie apocalypse majors).

1. Calculate the population mean and standard deviation for each quantitative random variable (height, weight, age, number of zombies killed, and years of education). NOTE: You will not want to use the built in var() and sd() commands as these are for samples.  
2. Use {ggplot} to make boxplots of each of these variables by gender.  
3. Use {ggplot} to make scatterplots of height and weight in relation to age. Do these variables seem to be related? In what way?  
4. Using histograms and Q-Q plots, check whether the quantitative variables seem to be drawn from a normal distribution. Which seem to be and which do not (hint: not all are drawn from the normal distribution)? For those that are not normal, can you determine from which common distribution they are drawn?  
5. Now use the sample() function to sample ONE subset of 30 zombie survivors (without replacement) from this population and calculate the mean and sample standard deviation for each variable. Also estimate the standard error for each variable, and construct the 95% confidence interval for each mean. Note that for the variables that are not drawn from the normal distribution, you may need to base your estimate of the CIs on slightly different code than for the normal…  
6. Now draw 99 more random samples of 30 zombie apocalypse survivors, and calculate the mean for each variable for each of these samples. Together with the first sample you drew, you now have a set of 100 means for each variable (each based on 30 observations), which constitutes a sampling distribution for each variable. What are the means and standard deviations of this distribution of means for each variable? How do the standard deviations of means compare to the standard errors estimated in [5]? What do these sampling distributions look like (a graph might help here)? Are they normally distributed? What about for those variables that you concluded were not originally drawn from a normal distribution?
