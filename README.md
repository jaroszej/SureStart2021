# SureStart2021 - Reflections

## This is a reflection document detailing my experiences and findings throughout the SureStart program
### February 08, 2021
_What do you hope to learn in this program?_  

I hope to gain some insight on how machine learning works, how the different algorithms are structured, and how to know what tool to use for each job. I also am excited to be able to work in a team of bright like-minded people. I hope the project we will work on for the make-a-thon phase of the program will be something I can learn a lot from.

### February 09, 2021
_What is the difference between supervised and unsupervised learning?_

Supervised learning typically is done in the context of classification. Simply put, it is the process of providing examples for a model to discover patterns within so that it will be able to re-identify those patterns on new datasets.
Unsupervised learning more commonly is tasked with clustering. That is, a mass dump of data is given to a model and the model will, in one way or another, discover ways to organize the data. 

_Describe why the following statement is FALSE: Scikit-Learn has the power to visualize data without a Graphviz, Pandas, or other data analysis libraries._  

This statement is false because Scikit-Learn is a library that is built on top of these other libraries. Data analysis libraries need to be installed first before you can use Scikit-Learn is a collective of these resources among others.

### February 10, 2021
_What are "Tensors" and what are they used for in Machine Learning?_  

Tensors are real world objects represented in a mathmatical way. They can represent multiple dimensions and can undergo transformations. In machine learning, a tensor is a generalization of vectors and matrices understood as a multidimensional array. Every Machine Learning model deals with tensors.

_What did you notice about the computations that you ran in the TensorFlow programs in the tutorial?_  

I noticed that there are several layers used to modify the input data in the process of "learning". Once data is normalized and passed through these layers the model is able to generalize.

### February 11, 2021  

The dataset I found was comprised of thousands of emails released from Enron, found here https://www.cs.cmu.edu/~./enron/ . The dataset provides a generous example of business and casual communication patterns between Enron employees and their contacts (with crucial information altered for privacy).
I believe this dataset could be used to build a model to detect phishing attempts through email. According to the [APWG Phishing Activity Trends Report](https://docs.apwg.org/reports/apwg_trends_report_q3_2020.pdf) for the 3rd Quarter of 2020, 128,926 phishing email attemps were reported in September alone. Over 350 thousand phishing emails were reported in the quarter. These reports are soley from APWG members and members of the public who report to the APWG website. To put it bluntly, there are a lot of phishing attempts through email. By examining datasets of ordinary work emails, such as the Enron email database, a model could be built to distiguish non-malicious from malicious emails.

### February 12, 2021  

I learned about Long/Short Term Memory (LSTM) and its use in NLP. I also learned about word embedding and about the process of Word2Vec embedding words into vectors to be used in LSTM neural networks.

### February 15, 2021  

Today, I learned about convolutional neural networks. Something I found interesting related to CNNs was some of the detection methods. Bounding box detection seems useful for outlining objects detected in pictures while landmark detection seems useful for highlighting the shape and characteristics of objects found in pictures.

### February 16, 2021
_How do you think Machine Learning or AI concepts were utilizied in the design of [this game](https://www.survivalofthebestfit.com/)?_

"Survival of the Best Fit" implemented a few concepts of ML and AI. Neural networks were used to learn from the patterns generated by the "hiring manager" of the game and generalize picking out additional candidates in an automated fashion. The game also implemented deep learning. There was a massive dataset (which could be selected from Google, Apple, or Amazon) of CV's to add into the model. This was supposed to make the algorithm better at selecting good candidates.
A key error that was made when training the model was that the data was not examined and corrected for biases. This was the main reason for the model's failure. In my experience, I chose to hire applicants based largely on their skill and ambition levels. I did not consider how many orange or blue applicants I was selecting. I happened to approve 70% or more orange applicants over blue applicants. It is important to note that I was not rejecting more blue applicants than I was rejecting orange applicants. The pool of applicants presented to me simply had more orange applicants. Despite my intention of hiring solely based on skill and ambition level, there was a bias latent in the data to prefer orange applicants due to their population in the accepted applicants category. This is an example of how ML and AI can reveal biases that are not so obvious to the developers who make them.

_Can you give a real-world example of a biased machine learning model, and share your ideas on how you make this model more fair, inclusive, and equitable? Please reflect on why you selected this specific biased model._

According to [a study](https://science.sciencemag.org/content/366/6464/447.abstract) published in the American Association for the Advancement of Science, a decision making algorithm used to guide health decisions showed evidence of racial bias such that Black patients assigned the same level of risk by the algorithm are sicker than White patients. It was estimated to be biased this way due to less money being spent on Black patients who had the same level of need as White patients. The researchers believe removing the cost value from the algorithm would remove the racial bias. This removal would increase the percentage of Black patients receiving additional help from 17.7% to 46.5%. 

_A Dive into Ethics: We must be mindful that AI and automated systems we train
could potentially, likely accidentally,
“learn” to be biased. Read [this article](http://gendershades.org/overview.html) and
discuss some of the ways that you intend to avoid algorithmic bias when
constructing AI projects._

It seems imperative to check for biases in training datasets before they are given to models for training to validate biases are being screened and identified. The article shows the training data contained more males over females by nearly 10% and contained more lighter skin over darker skin by around 7%. These are significant amounts and clearly enough to ingrain bias in a model.  
From my research, I have also found other inconspicuous variables to be related to these biases as well, such as using cost as a variable for a medical decision algorithm or using location to predict crime locations. These variables have latent reasons for their characteristics which can be rooted in stereotypical, prejudiced, and unjust history. It is important to consider these possibilities when implementing training data for ML and AI in projects. When models are being trained and biases are found to favor one subgroup over another it may even be fitting to create two separate models for each subgroup. Because these biases can have such a heavy impact on people in society, it is very important to recognize them before they are released to the public. 

### February 17, 2021
_Succinctly list the differences between a Convolutional Neural Network and a Full Connected Neural Network._

Convolutional Neural Networks (CNN) deal with image inputs. They are comprised of an input layer, a series of convolution and pooling layers, and fully connected (FC) layers, before an output layer. The input layer consists of the training set of images. Convolution layers and pooling layers work to summarize the presence of features in an input image. The convolution layer applies filters, called kernels, to the input that maps activations which indicate the locations and strength of a detected feature. The pooling layer will down sample feature maps by averaging or finding the max values of the feature. Fully connected layers in CNNs takes the results of the convolution and pooling process and uses them to classify the image to a label. The label is then returned in the output layer. CNNs are useful for object detection, feature extraction, and other image processing and identification functions.

A Fully Connected Neural Network (FCNN) consists of a series of fully connected layers where each neuron in on layer is connected to each neuron in the next layer. These types of NNs are the "jack of all trades" so to speak. They offer weaker performance than special-purpose networks but are  broadly applicable to many situations. Due to the high number of weights to train a FCNN, training time will be longer than specialized neural networks.
