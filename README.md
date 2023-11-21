# DSCI-D-590-Final-project

Objectives:
To develop a specialized language model that understands the nuances, structures, and language patterns of film scripts, ultimately aiding in script analysis, generation, and improvement.

Usefulness :
For scriptwriters facing creative blocks, the application can provide scene suggestions, dialogue ideas, or even whole plot arcs to spark inspiration.The application assists in refining and elevating the quality of film scripts by providing insights based on a vast dataset of existing scripts. It aids in narrative continuity, character development, and pacing.

While there are AI based scriptwriting software solutions like Plotbot and Jasper, they primarily focus on script analysis. Beyond just analysis, our application can generate content, offering writers direct, actionable content suggestions.

Our target users group are scriptwriters, filmmakers, film studios etc.

Data:
IMSDB is an online repository of film scripts consisting of approximately 1300 screenplays.Since the screenplays are stored in plain text on the site it made it relatively easy to design a scraper to iterate over each script url with Scrapy.
Dataset: Filtered the IMSDB dataset and selected Inglorious Bastards script for model generation
Dataset format: txt


Functionalities:

NLP Functions:
The NLP tasks the application performs are Text Analysis and Text generation. I have implemented LSTM architecture for Text generation. 
User interaction:

The possibilities for user Interaction through our app are:

1. If I work on the IMSDB dataset further.I would like to keep user interaction functionalities like:
->Maximum script length
->a text box for content required.
