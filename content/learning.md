Title: useful command in pyhton
Date: 2016-12-07 11:10
Category: Python

Some useful commands python
Python is a very powerful programming language. In this blog I am going to share some of cool stuff I learn during the GA program about python.


1) Ask a user to input a string:
reply = raw_input('Enter text, [type "stop" to quit]: ')

2) Ask a user to input a string:
reply = input("How many pounds does your suitcase weigh? ")

Note: In pyhton 2.x-
raw_input() takes whatever is typed on the console and returns it as a string.

input() takes whatever is typed on the console and evaluates it as a python statement. It is required that you type a syntactically correct statement.

In Python 3.x-

input() works the same way as raw_input() does in Python2. raw_input() is non-existent.


3) One of the cool things I learned was about .copydeepcopy(). In the following paragraphs I will tak about how and when we need to use this command.

Consider you generate a list of data. 

df = [1,2,3,4,5]

Then, you would like to generate a new list that has all the elements of the previous list except the first element. You probably do this:

df_new= df[1:]

Although, you did not change the original variable, when you print it, the original data also changes. 
So, what is the solution?

maybe the first solution that comes to your mind is:

df_copy = df

df_new= df_copy[1:]

It is interesting that this solution does not work either. The solution I found is to import a library called "copy" and use it to make a copy of 
the original data.

import copy
df_copy = copy.deepcopy(df)

df_new= df_copy[1:]

In this way you can make a copy from your data, modify the copy version without being worried about the original data. 



