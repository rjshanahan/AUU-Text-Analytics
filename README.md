## AUU-Text-Analytics
####A basic demo of text analytics using social media data

####*<a href="https://rjshanahan.shinyapps.io/shiny_AUU01" target="_blank">Interactively Explore AUU Twitter Sentiment Analysis</a>* 
  
#####Definitions for  <a href="https://rjshanahan.shinyapps.io/shiny_AUU01" target="_blank">interactive sentiment analysis visualisation</a>
|Attribute										| Description                  | Visualisation Use  |
|:---------------------------------------------------|:-------|:---------------------|
|sentiment   							| Natural language processing was used to determine the overall *sentiment* of the post - was it *positive, negative or neutral*	| ```colouring```	  |
|subjectivity   							| Natural language processing was used to determine the overall *subjectivity* of the post - was it *subjective or objective*	| ```colouring```	  |
|user   							| the *user* name used to create the post	| ```x-axis```	  |
|hashtag 							| the *hashtag* used in the posts where applicable	| ```x-axis```	  |
|like_fave					| the total *likes* or *favorites* given to the post	| ```y-axis```	  |
|share_rtwt					| the total *shares* or *retweets* given to the post	| ```y-axis```	  |
|posts					| the total number of *posts* by user or hashtag	| ```y-axis```	  |
|twitter					| the post source	| ```filter```	  |
Note: sentiment and subjectivity analysis was undertaken using the <a href="http://aylien.com/" target="_blank">Python API from Aylien </a>

![Aylien](http://aylien.com/images/graph.png)
