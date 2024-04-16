# CC-Jeopardy-Game-Model-and-Analysis

### Database Jeopardy Questions that I query with Pandas and build a working Game Model you can play!

Resources used in this project
- Jupyter Notebooks
- Python
- Pandas Library
- CSV file with every Jeopardy! question from September of 1984 to January of 2012 (over 200,000 questions)

### What can you see in the Analysis portion of the Notebook file?
1. Basic descriptive stats like the earliest and most recent show, total number of questions by round, etc
2. Lists of questions and answers by topic of your choice.  I chose "guitar", "chess", and "Yucatan", but you could alter it using my code
3. For each of these topics you can see total question counts, average dollar figure,  and most common answers.
   - For instance, there are 245 guitar related questions with an average value of $737 and the most common answer is Jimi Hendrix (12 times).
4. The most common question categories by round and the most common Final Jeopardy! answers
   - The most common Jeopardy! round categories are STUPID ANSWERS and POTPOURRI (255 questions each).
   - The most common Double Jeopardy! round category is BEFORE & AFTER (455 questions).
   - The most common Final Jeopardy! category is U.S. PRESIDENTS (50 questions).
   - The most common Final Jeopardy! answer is...... Canada!

### What can you do in the Game Model?
You can play the game, of course!  Run either cell that says "working game model" and start answering questions
The game will ask you if you want another question after every question you answer.  In this way, you can stop at any time.
It will keep track of your running balance and let you make a wager, up to the amount of your balance, for Final Jeopardy
You can become the Final Jeopardy! champion!

### What aspecs of this project were new to me, and taught me the most?
This was a very instructional project.  I love it!
- This was my first large project using Pandas DataFrames
- This was my first experience using regular expressions (regex) to do complex string pattern matching 
- Built a small dictionary using regex to use for replacements (eliminating commas, dollar signs, and blank spaces from strings before converting to floats)
- Used the .value_counts() method to get response frequencies
- In the working game model, I learned how to use a flag variable to stop an outer loop from running from inside a nested loop.  This was a critical step and one of the hardest to get my head around.
- Used .sample() to pull a random row from a DataFrame
- Solved an issue where names where answers that were names were being evaluated too critically (my model now accepts a last name or a first and last name)
- Forced the game model to end at any point that the user says they don't want another question
- Became familiar with f-string literals in place of .format()

### Play with the code, have fun, and tell me what you think!! 

