# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?
I learned how to work with lists and got very comfortable with them. I also learned how to better organize my code and functions in such a way that is easy to debug. My debuggin also improved as I navigated errors in my code. I was also able to better recognize what code that I hadn't written would do and how to add to it.


2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.
The user inputs a query which then goes through the match function. It then finds the pattern from the lists provided. From their, the variable words are extracted and then used to run functions that would return correct information such as actors or errors if something is not applicable.


3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use?
This could be useful for a website that has a lot of products or services to offer and customers might have more questions than what humans could realisticly answer. The chatbot would do it for the humans which makes it cheaper. The chatbot could be improved by understanding messages with slightly different formats or minor typos