# Assignment 3 - Writeup

Assignment 3 is all about creating this natural language query system.  In order to do so, you have to write a lot of functions to retrieve infomation.  You will also have to write a function to return answers from a pattern-action list.  There is a lot of work to accomplish in this assignment, but this portion is intended for you to write about what you accomplished.

## Reflection Questions
1. In your own words describe the `search_pa_list` function.
"search_pa_list" takes user input and then utilizes the match tool to find a pattern. If a pattern is found, it checks to see if it correlates with one of the actions. The action will then return a list to answer the user's query.

2. What movie did you add to the `movies.py` file?  What year was it made? Any specific reason you added that movie?
I added high school musical to the movies.py file. It was made in 2006 and I really love the music and choreography.

3. What pattern / action did you add to the paList data structure?  Why do you think that is a useful pattern / action?
 I added (str.split("what movies did % direct"), title_by_director),
 I think this is helpful because it is another common way of asking the movies that were directed by a director.


4. What is chatbot would you create that would be like this?  Describe why you would create it and what it would do.
I would create a chatbot with Taylor Swift albums. It could have all of her albums, songs, and information about the number of times each song was streamed. I would create it because I am a Taylor Swift fan and not enough people know enough about taylor. I might walk up to somebody and say, "When did taylor write her first song" and people are like "what" and im like "you shoulnd know this. get with it!"

5. What was the most difficult portion of this assignment?
The most difficult portion of this assignment was understanding how all of the actions and pa_list worked together. I did not understand it at first, but as I kept writing the code it made more sense. 

6. Did you write a new assert for your pattern action?
yes


