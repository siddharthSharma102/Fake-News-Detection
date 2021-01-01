Thanks for visiting!

# Fake-News-Detection

### MODELS USED:
**1.** CNN <br>
**2.** DEEP CNN <br>
**3.** LSTM <br>
**4.** Multi-Channel CNN <br>

### ACTIVATION FUNCTIONS USED:
**1.** Sigmoid <br>
**2.** Relu <br>
**3.** Softmax <br>

### OPTIMIZATION ALGORITHM USED:
**1.** Adam <br>

### DATASET USED:
Due to the size of dataset size I have uploaded it on google drive, link to the drive is given below.

### GloVE WORD EMBEDDING:
Due to the size of dataset size I have uploaded it on google drive, link to the drive is given below.


### SOMETING ABOUT THE PROJECT:
Fake news existed for a very long time; the spread of fake news got a boost with the invention of printing press. Fake news is news consisting of deliberate disinformation or hoaxes spread via traditional news media or online social media. Traditional News Channels and Social media are most and widely used sources for spreading fake news. Social media has many pros and cons. On the one hand, it’s cheap, easy to access, and rapid dissemination of information lead people to seek out and consume news from social media. On the other hand, it enables the wide spread of fake and misleading news. Users on social media tend to form groups of like-minded users where they express their emotions, resulting in an echo-chamber effect. <br><br>
Blogs have become another widely used media for spreading news. Many users on social media use it as a means of spreading false news. In some cases the users are merely pre-programmed social bots, i.e. a computer controlled by a set of instructions to generate content and interact with other users.  
Detecting this fake news poses several challenging research problems. Fake news is used in many ways to influence the citizens by politicians or a certain group of individuals for personal gain. Fake news are generally spread by propagandist to convey some political or influence. Excessive spreads of fake news have serious negative impact on the society. Therefore, fake news detection on social media has recently become an emerging research that is attracting tremendous attention. The challenge of detecting fake news comes from the fact that it is difficult even for humans to separate fake news from the original news. Misleading users often blend the original news with false details, which makes it easy to get people’s attention towards the original news without noticing the fabricated parts. <br><br>
Lately researchers have tried to solve this problem using deep learning. Building a model involves – selecting dataset, deciding upon the algorithm or model to be used and executing the model with high accuracy. CNN, RNN & LSTM are widely used. CNN can be used for both classifying texts and images and RNN & LSTM are used with for classifying text. <br><br>
Long-Short Term Memory (LSTM) architecture can be used using keras. LSTM has feedback connections and can not only process images but also entire video or text. It consists of an input gate, a cell, an output cell and a forget cell. <br><br>
Sentence Modelling is one of the first steps that we use for representing sentences as meaningful features for tasks such as classification. Cleaning of dataset involves removal of punctuations, removal of HTML tags, changing the case of the text, lemmatizing, stammering, etc. <br><br>
Text in a dataset often comes in paired-words, so the co-occurrence of words in a corpus can reveal us something about it, in short we create a list of properties describing a particular word. 
GloVe is an unsupervised learning algorithm for obtaining vector representations for words. Training is performed on global word-to-word co-occurrence statistics from a corpus, and the results of these embedding shows interesting linear structures of the word vector. GloVe collects word c-occurrence in form of a word co-occurrence matrix X. <br><br>
