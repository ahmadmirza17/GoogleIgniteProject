# GoogleIgniteProject
Course Recommendation
We collected the user interests in a csv and the list of courses in another csv, we multiply the user interest index for each catogery 
by the catagorical name and make these into a sentence.
We then use the universal sentence encoder to encode both the course names and the sentence of interests for each user.
Then we calculated the cosine similarity between each users interest sentence and the course names.
We then picked the top 3 most relevant courses based on the users' interests and recommend this to the user.
