# News-Categorizer
#An automatic system which uses extractive summarization to categorize text after extracting it from news paper clips, i.e. semantic chaining in combination with feature extraction.
Today we have lots of information to read from a lot of sources like books, papers, news articles, emails, internet media, etc. On the other hand, humans always have a lack of time and are always in a hurry. So it's important for them to know all the information which can help them.
This is only possible when they just read the important facts and info which will not only let them know about the event but also save a lot of their time. To achieve this, summarization of text articles is very useful. We will also use the tagging algorithms on the text to tag them with relative topics and the user can also see the domains in which the particular article belongs and select or reject to read that. 
Recommendation systems can be built on top of it to recommend the related articles based on the tags which the user visits the most and the sense of articles that the user is interested in. This will ensure that all the desired information is reached to the users and also they achieve this in very less amount of time.

The proposed methodology contains many modules as described in the above flowchart. Some modules depend on previous modules and some modules are independent of others. Proposed methodology is explained below:

### Input: Image of news article
### Output: Summarization and tagging of news article

The algorithms used in this model are shown in the above figure. The steps are as follows:
![GitHub Logo](/images/logo.png)
### 1) Image as an input
Image inputs are provided to the model. The input images can be of varied sizes. They are converted to the same fixed size to enhance the efficiency of processing and reduce the time of execution.

### 2) Extract text from image
Then the text is extracted from images. As the input images can contain many types of media and languages like images inside the input image which should be ignored to extract only the meaningful text.
This step helps in getting all the text that is present in the images.

### 3) Pre-processing of extracted text
The text that is now obtained from the last step may contain some erroneous words also called bogus words. These words should be ignored as they can adversely affect the accuracy and efficiency of this model. Then it performs lexical analysis, stop word elimination, tokenization, stemming and POS taggingthat can help in improving the context of the text and improve the results that it obtains.
