# Stopwords

![alt text](https://miro.medium.com/max/1400/1*sZIbOQeo3pxx3YWyDknM7g.png)

Stop words are words that are deemed unimportant during communication, and listeners can comprehend the speaker's message without the use of these words.
# What has been done?

I have created a Python function within this document, which accepts a sentence as input, eliminates any stop words within the sentence, and returns the modified sentence without those stop words.

# Steps Performed

![alt text](https://th.bing.com/th/id/R.8a383c9d6d3686bd754d8a67099eef7a?rik=AwFcmLrZC3VhKg&riu=http%3a%2f%2fdrkarishmaahuja.com%2fwp-content%2fuploads%2f2020%2f09%2fstair_animations.gif&ehk=huBKh5i6rH%2fg8q3VpF96WM55QpjSGT%2bczAvnnJ85FLg%3d&risl=&pid=ImgRaw&r=0)

1. The sentence was tokenized to split it into individual words. 
2. Then, a loop was created to iterate over each word and verify if it was present in the list of stop words. 
3. If a word was found in the stop word list from Python's library, the function would skip it.  
4. Finally, the output was the original sentence with all stop words removed.
