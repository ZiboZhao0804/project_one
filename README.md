# Project_One

## In this project, we will be using Covid-19-API to analyze Covid related data around the world.

### Please refer to the documentation here: 
- https://github.com/M-Media-Group/Covid-19-API


## Analysis Goals:

### Part I: Live cases data
https://covid-api.mmediagroup.fr/v1/cases


### Part II: Historical cases data
https://covid-api.mmediagroup.fr/v1/history


### Part III: Vaccines data
https://covid-api.mmediagroup.fr/v1/vaccines

### Part IV: Make your own search
* I'm also thinking using 'input' function to allow users to enter the countries they would like to search and put them into a list. 
* This can be separated from the first three parts of analysis. Then, we can show the data in a map using Google Geocode, Google Places and gmaps, including the information as a marker layer in gmaps and the number as a heat layer.


## For each part I - III, we will go through the following analysis in individual jupyter notebook:

1. Collect data from API and put the data into one csv file. You can use the above links as the base_url.<br /> 
   **There are different parameters we can choose from for each endpoint. We probably want to narrow down to a specific list of countries or status to make our own stories! 

2. Clean up the data. Only save the columns of interest and drop any NA. May also need extra columns, eg. percentage of cases over total population etc.

3. Generate plots and perform statistical analysis.

4. A summary of findings.

## Extra notes:

* There is no api_key required for Covid-19-API. However, after the initial data analysis, we may be incorporating our data and show on the gmaps using google Geocode and google Places. So I added the config.py to .gitignore to hide our keys.

* Below is a starter code that may help, but feel free to start in your own ways.

* I will incude this part as a README.md in our repositories Project_One. I grant access to everyone, you can change the content and I will merge the edits from everyone. Seara and I already have a branch in this repo :)<br /> 
<span style="color:red">Please send me your username on github. You will receive an invitation from me.</span>

* After you get access to the repo, you can do the following to make a directory in your local workspace and add your branch:
- *git clone git@github.com:ZiboZhao0804/project_one.git*
- *git checkout -b YOUR_NAME_HERE*
- *git push --set-upstream origin YOUR_NAME_HERE*

*<span style="color:blue"> We can decide how we would like to proceed with "division of labor" later in the class or anytime via Slack. Since we have four people in our team, I'm thinking one part per person , so that all of us can have some pratice of the workflow above. The four parts can be done in parallel, and after that, we can work together to put all together. </span>

*<span style="color:blue"> We can also come up with a timeline for our tasks so that we have enough time to put everything into a final presentation.</span>
