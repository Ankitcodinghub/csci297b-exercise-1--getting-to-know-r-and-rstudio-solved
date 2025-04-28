# csci297b-exercise-1--getting-to-know-r-and-rstudio-solved
**TO GET THIS SOLUTION VISIT:** [CSCI297B Exercise 1- Getting to Know R and Rstudio Solved](https://www.ankitcodinghub.com/product/csci297b-exercise-1-getting-to-know-r-and-rstudio-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117363&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI297B Exercise 1- Getting to Know R and Rstudio Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
1. Log on to the RStudio Workbench Server.

2. Change your global options so that the .RData save and restore is off.

3. Create a new RStudio Project (select File→New Project on the main menu). Create the Project in a new directory by selecting ‘New Directory’ and then select ‘New Project’. Give the Project and folder the name project_01_yourname in the ‘Directory name:’ box and choose where you would like to create this Project directory by clicking on the ‘Browse’ button.

The name you use should start with your last name, whatever name is used to alphabetize you in a listing of students. That way I can find your project quickly.

Finally create the project by clicking on the ‘Create Project’ button.

5. Now create a new R script inside this Project by selecting File→New File→R Script from the main menu (or use the shortcut button). Before you start writing any code save this script by selecting File→Save from the main menu. Call this script exercise_1 (remember, file names should not contain spaces!). Click on the ‘Files’ tab in the bottom right RStudio pane to see whether your file has been saved in the correct location.

# csci297b Exercise 1

# Geoffrey Matthews

# Exploring R and Rstudio

1

2

3

4

7. Explore RStudio making sure you understand the functionality of each of the four windows (see Section 1.3 of the Introduction to R book for a summary and/or watch this video). Take your time and check out each of the tabs in the windows. The function of some of these tabs will be obvious whereas others won’t be useful right now. In general, you will write your R code in the script editor window (usually top left window) and then source your code into the R console (usually bottom left) by clicking anywhere in the relevant line of code with your mouse and then clicking on the ‘Run’ button at the top of the script editor window. If you don’t like clicking buttons (I don’t!) then you can use the keyboard shortcut ‘ctrl + enter’ (on Windows) or ‘command + enter’ (on Mac OSX).

8. Now to practice writing code in the script editor and sourcing this code into the R console. In your script type help(’mean’) and source this code into the console. Notice that the help file is displayed in the bottom right window (if not then click on the ‘Help’ tab). Examine the different components of the help file (especially the examples section at the end of the help file).

9. The content displayed in the bottom right window is context dependent. For example if we write the code plot(1:10) and source it into the R console the bottom right window will display this plot (don’t worry about understanding the R code right now, hopefully this will become clear later on in the course!).

10. Next, let’s practice creating a variable and assigning a value to this variable. Create a variable called first_num and assign it the value 42. Click on the ‘Environment’ tab in the top right window to display the variable and value. Now create another variable called first_char and assign it a value ”my first character”. Notice this variable is now also displayed in the ‘Environment’ along with it’s value and class (chr – short for character class).

11. Remove the variable first_num from your environment using the rm() function. Check out the ‘Environment’ tab to ensure the variable has been removed. Alternatively, use the ls() function to list all objects in your environment.

12. Let’s see what happens if we assign another value to an existing variable. Assign the value ”my second character” to the variable first_char you created above. Notice the value has changed in the ‘Environment’. To display the value of first_char enter the name of the variable in the console. Don’t to forget to save your R script periodically!

13. OK, let’s leave RStudio for a minute. Using your favourite web browser, navigate to the R-project website and explore links that catch your eye. Make sure you find the R manuals page and the user contributed documents section.

14. Click on the ‘Search’ link on the R-Project website. Use ‘Rseek’ to search for the term ‘mixed model p values’ (this is a controversial subject!) and explore anything that looks interesting. Learning how to search for help when you run into a problem when using R is an acquired skill and something you get better at over time. One note of caution, often you’ll find many different solutions to solving a problem in R, some written by experienced R users and others by people with less experience. Whichever solution you choose make sure you understand what the code is doing and thoroughly test it to make sure it’s doing what you want.

16. Another strategy would be to use the help.search() function to search through R’s help files. Search the R help system for instances of the character string ‘plot’. Take a look at Section 2.5.1 for more information. Also, see if you can figure out how to narrow your search by only searching for ‘plot’ in the nlme package (hint: see the help page for help.search()).

17. R’s working directory is the default location of any files you read into R, or export from R. Although you won’t be importing or exporting files just yet it’s useful to be able to determine what your current working directory is. So, read Section 1.7 of the Introduction to R book to introduce yourself to working directories and figure out how to display your current working directory.

18. Don’t to forget to save your R script. Close your Project by selecting File→Close Project on the main menu.

19. Remember to share your project with me!
