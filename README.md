# Twitter-Bot
Created a twitter bot that is supposed to do the following things:
1. Follow everyone who is following me.
2. Favorite and Retweet a Tweet based on Keywords.
3. Reply to a user based on a keyword.

All this is done using 2 packages of twitter in Python:
1. Tweepy
2. Tkinter

Tweepy is used to get the necessary tokens of the consumer (user) and the access to the Twitter account and also allows to reply, retweet and favorite the tweet that he wants based on the keyword search. All this is done withi a function, so that not all the codes have to be run seperately and the user has to only call the function in order to execute it.

In order to make it more simple and allow the user to reply, retweet or favorite a tweet, a GUI is created and it allows the user to enter the keyword and select what he/she wants to do with the tweet. This GUI is created using tkinter package of twitter in Python. You can also mention the number of tweets that you want to either reply, retweet or favorite to by entering the number of tweets in the GUI.

In order to run the code for replying and retweeting seperately as singular code (for testing purpose), they have been added at the end.

And since, this was for my twitter account, and I had already tested the code for followers, error is thrown for that part of the code which can be ignored.

Check the updated folder: #TwitterBot_Updated
