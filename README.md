# DSCI-D-590-Final-project

Objectives:
To develop a specialized language model that understands the nuances, structures, and language patterns of film scripts, ultimately aiding in script analysis, generation, and improvement.

Usefulness :
For scriptwriters facing creative blocks, the application can provide scene suggestions, dialogue ideas, or even whole plot arcs to spark inspiration.The application assists in refining and elevating the quality of film scripts by providing insights based on a vast dataset of existing scripts. It aids in narrative continuity, character development, and pacing.

While there are AI based scriptwriting software solutions like Plotbot and Jasper, they primarily focus on script analysis. Beyond just analysis, our application can generate content, offering writers direct, actionable content suggestions.

Our target users group are scriptwriters, filmmakers, film studios etc.

Data :
I am looking on two different datasets:

1. Tv Show subtitles dataset from https://www.kaggle.com/datasets/albenft/game-of-thrones-script-all-seasons
I have attached this csv file above
Dataset format: csv

->This dataset contains columns like season, episode, character name, dialogue.
-> In data cleaning, we can look for NA values.

2. IMSDB is an online repository of film scripts consisting of approximately 1300 screenplays.Since the screenplays are stored in plain text on the site it made it relatively easy to design a scraper to iterate over each script url with Scrapy.
I am yet to scrape this data.
Dataset format: json


Functionalities:

NLP Functions:
In both the dataset cases, the NLP tasks the application performs are Text Analysis and Text generation. If I work further on the IMSDB dataset,  I am planning on using Language models like GPT-2 , BERT etc. If I work further on the TV show dataset, I am planning on using models like Neural Networks, transformers.

User interaction:

The possibilities for user Interaction through our app are:

1. If I work on the TV shows dataset further. I would like to keep user interaction functionalities like:
-> selecting the tv show format in which they want to generate the dialogues.
->A text box to enter the initial words with which the dialogue should start.
-> A filter specifying the maximum length of the dialogue.

2. If I work on the IMSDB dataset further.I would like to keep user interaction functionalities like:
->Maximum script length
->a text box for content required.
