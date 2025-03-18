# WGU Chatbot

  The Amy WGU Chatbot is implemented to help guide students into a career track based on their responses to their personality style. The Chatbot first responds to “Hello” in the chat. It then asks the student if they are more logic or visual focused as a person. Depending on what is selected, it then asks a follow up question with choices for what a person prefers. Based on that response, the chatbot gives a career suggestion with a link to Coursera to find out more about it. For example, if a student were to say they are logic focused and then select “I like to build and create projects” they would receive the response of Back End Developer and a link to Coursera with more information about what a Back End Developer does.

  Logic Pathway: Back End Developer, Data Analyst, Cyber Security Analyst.
	Visual Pathway: Font End Developer, UX Designer.

 For the chatbot, I used choices with buttons to help facilitate the student to picking a choice. The buttons then call the next pattern which has a selection of 2-3 different options. Based on the button they select, it then calls the final pattern which gives them their career suggestion. For example, if the student selects they are a visual learner and then selects “I like to organize how things look” they are given the result “It seems like a UX Designer would suit you well! Click here to learn more!” The second statement is hyperlinked to the Coursera website to give more information about UX Design. If the student were to select logic and then select “I like working with data and statistics” they are given the result “It seems like a Data Analyst would suit you well! Click here to learn more!” The second statement is hyperlinked to the Coursera website to give more information about Data Analytics. 
	The cases (the five different job types) were selected, because they are some of the more popular roles in the software development field. UX Designer is the only one that is slightly adjacent, but is integral for the field as well. The button choices were designed with descriptions at a higher level for each of the jobs. For example, “I like to build and create projects” would lead to Back End Developer as an option, because back-end developers work on the core functions of building and creating projects and focusing on their functionality.

## Installation Guide

To try out the chatbot on Pandorabot’s website type in WGU Amy Bot into the search bar at this address: https://home.pandorabots.com/dash/bot-directory
To install WGU Amy Bot: Open Pandorabots > Click on Sign In at the top right > Once you are signed in, click Go To Dash > Click File > Upload the zip file provided during submission (make sure to unzip at the time of upload) > Push to Repo to add to any GitHub project you are currently working on.


### Strengths and Weaknesses of the Chatbot

  Strengths:   
  
-Pandorabots is very straightforward to develop. All that’s required is knowing how the patterns work. Because of how easy it is to select patterns with buttons it was very easy to create the chatbot and implement different career choices and links to go along with them
-Pandorabots also has a lot of features that can be used that weren’t implemented in this chatbot. If I were to make the chatbot more complex, it could pull from the user’s response and repeat back words, it can display logos/pictures, it can have multiple responses for the same pattern to make it feel more alive, etc.


   Weaknesses:   

-While Pandorabots is very straightforward, one of its weaknesses is it can be quite lengthy in the coding. Patterns take up a lot of space and there doesn’t appear to be any use of functions or recursion that could help optimize this.
-Pandorabots also is limited in that you can’t really use machine learning with it. It’s just picking up a word that’s said and applying a response. This puts the burden on the developer to make the chat bot feel more ‘real’ and more like AI. 
