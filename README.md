# sentiment-classifier

**Author**: Raven Delaney
**Version**: 1.0.0

## Overview
<!-- Provide a high level overview of what this application is and why you are building it, beyond the fact that it's an assignment for a Code Fellows 401 class. (i.e. What's your problem domain?) -->
Intro to using a sentiment classifier for machine learning

## Getting Started
<!-- What are the steps that a user must take in order to build this app on their own machine and get it running? -->
Jupyter notebooks can be run online or in VS code(simply a matter of personal preference)
I prefer running it in VS code so my color scheme and whatnot are to my preferred settings.
Once you're in the notebook, run all cells to see the data collection and what each function does to the data

## Architecture
<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you're using, and any other relevant design information. This is also an area which you can include any visuals; flow charts, example usage gifs, screen captures, etc.-->
Using command line and vs code, I started a jupyter notebook that takes in a csv and returns various bits of information based on the functions that go into the notebook.
Jupyter notebooks are amazing for data visualization because they take in regular python functions and can return actual models of data in various forms(my experience is limited to some graphs)
I imported pandas, numpy, tensorflow, and json to this particular notebook.


## Architecture
<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you're using, and any other relevant design information. This is also an area which you can include any visuals; flow charts, example usage gifs, screen captures, etc.-->
For each rating number, I attached a sentiment classifier. 4 and 5 are given a 2, 3 is given a 1, and 2 or 1 are given a 0.


## API
<!-- Provide detailed instructions for your applications usage. This should include any methods or endpoints available to the user/client/developer. Each section should be formatted to provide clear syntax for usage, example calls including input data requirements and options, and example responses or return values. -->
sentiment - takes rating of 1 through 5 and assigns a sentiment to each number
floats - holds scores at integer
hotels_reviews - returns the text reviews with number review, and sentiment number columns


## Change Log

<!-- Use this are to document the iterative changes made to your application as each feature is successfully implemented. Use time stamps. Here's an example:
01-01-2001 4:59pm - Added functionality to add and delete some things.
-->
12/30/2019 11:30pm - pre-processed data for sentiment classification
01/01/2020 - started notebook
01/05/2020 6:03 pm - added to readme and added comments to notebook


