# SureStart2021 - Reflections

## This is a reflection document detailing my experiences and findings throughout the SureStart program
###February 08, 2021
_What do you hope to learn in this program?
I hope to gain some insight on how machine learning works, how the different algorithms are structured, and how to know what tool to use for each job. I also am excited to be able to work in a team of bright like-minded people. I hope the project we will work on for the make-a-thon phase of the program will be something I can learn a lot from.

###February 09, 2021
_What is the difference between supervised and unsupervised learning?

Supervised learning typically is done in the context of classification. Simply put, it is the process of providing examples for a model to discover patterns within so that it will be able to re-identify those patterns on new datasets.
Unsupervised learning more commonly is tasked with clustering. That is, a mass dump of data is given to a model and the model will, in one way or another, discover ways to organize the data. 

_Describe why the following statement is FALSE: Scikit-Learn has the power to visualize data without a Graphviz, Pandas, or other data analysis libraries.
This statement is false because Scikit-Learn is a library that is built on top of these other libraries. Data analysis libraries need to be installed first before you can use Scikit-Learn is a collective of these resources among others.

###February 10, 2021
_What are "Tensors" and what are they used for in Machine Learning?
Tensors are real world objects represented in a mathmatical way. They can represent multiple dimensions and can undergo transformations. In machine learning, a tensor is a generalization of vectors and matrices understood as a multidimensional array. Every Machine Learning model deals with tensors.

_What did you notice about the computations that you ran in the TensorFlow programs in the tutorial?
I noticed that there are several layers used to modify the input data in the process of "learning". Once data is normalized and passed through these layers the model is able to generalize.

###February 11, 2021
The dataset I found was comprised of thousands of emails released from Enron, found here https://www.cs.cmu.edu/~./enron/ . The dataset provides a generous example of business and casual communication patterns between Enron employees and their contacts (with crucial information altered for privacy).
I believe this dataset could be used to build a model to detect phishing attempts through email. According to the [APWG Phishing Activity Trends Report](https://docs.apwg.org/reports/apwg_trends_report_q3_2020.pdf) for the 3rd Quarter of 2020, 128,926 phishing email attemps were reported in September alone. Over 350 thousand phishing emails were reported in the quarter. These reports are soley from APWG members and members of the public who report to the APWG website. To put it bluntly, there are a lot of phishing attempts through email. By examining datasets of ordinary work emails, such as the Enron email database, a model could be built to distiguish non-malicious from malicious emails.

###February 12, 2021
I learned about Long/Short Term Memory (LSTM) and its use in NLP. I also learned about word embedding and about the process of Word2Vec embedding words into vectors to be used in LSTM neural networks.

###February 15, 2021
Today, I learned about convolutional neural networks. Something I found interesting related to CNNs was some of the detection methods. Bounding box detection seems useful for outlining objects detected in pictures while landmark detection seems useful for highlighting the shape and characteristics of objects found in pictures.
