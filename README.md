# TextWiz
FYP Fall 2019

<p align="center"> 
    <img src="TextWiz/Images/TextWizLogo.ico" alt="alternate text">
</p>

A Qualitative Data Analysis Software. This projectâ€™s main purpose is to provide an open source software to analyze text documents to understand perceptions, identify concepts, key ideas, interesting patterns and extract useful knowledge to support decision makings for the user.

## Main Features Include:

- Import data/text using different file formats, web and social media
- Study word frequency, distributions and patterns.
- Find key words in context.
- Tag/annotate text.
- Sentiment Analysis
- Explore connections between sources for insights and meaning.
- Visualizations include tables, graphs, word clouds and trees.
- Survey Analysis

## Requirements
1. Python 3.x
2. Internet Connection

## Setup and Install requirements
Enter these commands on cmd to install all required dependencies
 
1. python -m pip install --upgrade pip command
2. pip install wheel
3. pip install -r requirement.txt 
4. pip install pywin32 (**For Windows Only**)
6. python -m nltk.downloader all
6. python -m spacy download en_core_web_sm

(Note: If you get a visual c++ requirement error please download and install MS visual build tools)
	https://visualstudio.microsoft.com/visual-cpp-build-tools/

7. If you want to use social network analysis you will need an api key for google and twitter. You can obtain the api keys from <a href = "https://console.developers.google.com/projectselector2/apis/dashboard">Google Developer</a> and <a href = "https://developer.twitter.com/en">Twitter Developer</a> and enter the keys in the following file and line numbers.

   ### For Twitter
        File Name: DataSource.py
		1. Line 521:  Consumer Key
		2. Line 522:  Consumer Secret
		3. Line 523:  Access Token
		4. Line 524:  Access Token Secret 

   ### For Youtube
	#### For Extracting Comments from Video URL    
		Generate YouTube Data API v3 Key and paste it in
		File Name: DataSource.py
		Line 580: Youtube API key
    
	#### For Extracting Comments by Using Keyword
		Generate YouTube Data API v3 OAuth 2.0 Client IDs
		Download the JSON file  
		Rename it to "client_secret.json" 
		Move and Replace the file to "TextWiz/Youtube/" 
            
## How to use this software
1. Clone the repo
2. Open cmd and change path to current directory
3. Run the following command:
	python TextWiz.py


## Website Link
https://mfarmalkhan.github.io/TextWiz_Website/
