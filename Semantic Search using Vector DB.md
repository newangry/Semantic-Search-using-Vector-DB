# What’s Semantic search

Semantic search is a set of search engine capabilities, which includes understanding words from the searcher's intent and their search context. This type of search is intended to improve the quality of search results by interpreting natural language more accurately and in context.

# What are Vectors?

When we talk about vectors in the context of machine learning, we mean this: Vectors are groups of numbers that represent something.
That thing could be an image, a word, or nearly anything.
As a summary, though, machine learning models input items (let’s assume just words from here on out) and try to figure out the best formulas to predict something else.
For example, you may have a model that takes in the word “bee,” and it is trying to figure out the best formulas that will accurately predict that “bee” is seen in similar contexts as “insects” and “wasps.”
Once that model has that best formula, it can transform the word “bee” into a group of numbers that just so happen to be similar to the group of numbers for “insects” and “wasps.”

# How Vector Search Works?

Vector search does this by taking those groups of numbers we described above and having the vector search engine ask, “If I were to graph these groups of numbers as lines, which would be closest together?”
An easy way to conceptualize this is to think of groups that have just two numbers. The group [1,2] is going to be closer to the group [2,2] than it would be to the group [2,500].
(Of course, since vectors have dozens of numbers within them, they are being “graphed” in dozens of dimensions, which isn’t so easy to visualize.)
This approach to determining similarity is powerful because the vectors representing words like “doctor” and “medicine” are going to be “graphed” much more similar than the words “doctor” and “rock” would be.

# What are the elements of Semantic Search?

Semantic search applies user intent, context and conceptual meanings to match a user query to the corresponding content.
It uses Vector search and machine learning to return results that aim to match a user’s query. These components work together to retrieve and rank results based on meaning.
These components work together to retrieve and rank results based on meaning. On of the most fundamental pieces is that of context.

# Plotting Vectors to find Similarity

This is generally how vector search works as well.
A machine learning model takes thousands or millions of examples from the web, books, or other sources and uses this information to then make predictions.
Of course, it is not feasible for the model to go through comparisons one-by-one ( “Are Toyota Prius and hybrid seen together often? How about hybrid and steak?”) and so what happens instead is that the models will encode patterns that it notices about the different phrases.
It’s similar to how you might look at a phrase and say, “this one is positive” or “that one includes a color.”
Except in machine learning the language model doesn’t work so transparently (which is also why language models can be difficult to debug).
These encodings are stored in a vector or a long list of numeric values.
Then, vector search uses math to calculate how similar different vectors are.
Another way to think about the similarity measurements that vector search does is to imagine the vectors plotted out.
This is mind-blowingly difficult if you try to think of a vector plotted into hundreds of dimensions.
If you instead imagine a vector plotted into three dimensions, the principle is the same.
These vectors form a line when plotted, and the question is: which of these lines are closest to each other?
The lines for “steak” and “beef” will be closer than the lines for “steak” and “car” , and so are more similar.
This principle is called a vector, or cosine, similarity.
Vector similarity has a lot of applications.
It can make recommendations based on the previously purchased products, find the most similar image, and can determine which items best match semantically when compared to a user’s query. 

