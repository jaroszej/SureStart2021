# SureStart2021

## Responses
### DAY 1 Feb 08, 2021

_What do I hope to gain from the SureStart program?_

  I am eager to gain a lot from SureStart. I am excited to have hands-on experience with ML and AI and I am excited for the professional skills this program will help me develop. I am excited to experience working in a team of talented people and I hope to learn from them as much as I can from the SureStart program itself. I am nervous about presenting a project for the make-a-thon in the final 2 weeks, yet I am still excited to gain experience speaking for a project I will be proud to have developed.

### DAY 2 Feb 09, 2021

_What is the difference between supervised and unsupervised learning?_

  With supervised learning, the program is given a data set of examples for it to follow and generalize on new experiences in the future. Typically, the ultimate goal is to develop a finely tuned predictor function.
Unsupervised learning allows the program to develop patterns and relationships when given a huge data set and one or a multitude of goals.

_Why is the statement 'Scikit-learn has the power to visualize data without another data analysis library' false?_

  Scikit-learn is a library comprised of supervised and unsupervised learning algorithms that is built on top of the SciPy stack, which includes NumPy, SciPy, Matplotlib, IPython, Sympy, and Pandas. These other libraries must be installed before scikit-learn can be used.
Scikit-learn is focused on modeling data. For loading, manipulating, and summarizing data, refer to NumPy and Pandas.

### DAY 3 Feb 10, 2021

_What are "Tensors" and what are they used for in Machine Learning?_

  A tensor is a representation of a physical entity with a magnitude and multiple directions. 
In computer science, a tensor is a multi-dimensional array. With this in mind, we can refer to a number to be a 0 dimension tensor, an array to be a 1 dimension tensor, and a 2d-array to be a 2 dimension tensor. In corresponding mathematics terms, these are a scalar, a vector, and a matrix.
  Tensors have three attributes: rank, axes, and shape. A tensor's rank describes the number of dimensions within the tensor. This number describes how many indices are required to refer to a specific data element in the tensor data structure. An axis of the tensor is a specific dimension of the tensor. The shape of a tensor is determined by the length of each axis. This describes how many indices are in each axis.
  In machine learning, tensors are used to represent data.

_What did I notice about the computations ran in TensorFlow programs in the [tutorial](https://www.datacamp.com/community/tutorials/tensorflow-tutorial)?_

  In TensorFlow, every computation involves a tensor. We can use functions to modify and extrapolate information from tensors. We can inquire about the size and shape of a tensor and we can also alter the shape as needed.
When we have data that is properly manipulated to be useful we can begin deep learning.
  
### DAY 4 Feb 11, 2021

_Think about a real-world problem and see if you can find a dataset that has the
characteristics of the data of that problem. Then, think about the deep learning
algorithm that you would likely use to develop a solution to it. Outline why you
picked a particular approach._

APWG (Anti-Phishing Working Group, Inc.) received 201,591 reports of phishing email attempts from its member companies, Global Research Partners, APWG website report submissions, and through email submissions in the third quarter of 2020. ["Phishing Activity Trends Report for Q3 2020"](https://docs.apwg.org/reports/apwg_trends_report_q3_2020.pdf). 
Many attacks will target the recipient specifically (spear phishing), increasing the chances that the email is not detected as malicious. These attacks can result in huge breaches of security which lead to the release of private and personal information. Parties who are less familiar with technology, such as the elderly can especially be susceptible to falling for the attack. 
Deep learning could be implemented to identify language used in phishing emails and learn to flag phishing attempts for users. Text classification algorithms would be useful for this problem. Convolutional Neural Networks (CNN) are ideal for document classification because they are able to pick out key features regardless of their location in a document. With a CNN, a model could be trained to find key words phishing attackers use to try to pry data from email recipients. Going forward, future models should be able learn based on more modern examples of phishing emails that can be reported by recipients. After all, phishing attempts continue to advance and evolve to become harder to identify.

_Thinking about ethical concerns when applying or using machine learning_

There are many pressing ethical concerns when applying or using machine learning. There have been instances of models which perpetuate unjust situations due to being trained on a biased dataset.
In 2012, Chicago’s police department implemented a predictive police surveillance system, the Party to Violence Program (PTV). It implemented biased data with irresponsible oversight. The program recorded nearly 400,000 individuals in one version of the model. People who were arrested but not convicted were left in the system and people who were arrested for nonviolent offenses were also included. Only 16.3 percent were confirmed to be gang members. The program ultimately exacerbated racial disparities and was a shining example of unethical policing. It was discontinued November 1, 2019.
Examples like Chicago's predictive police algorithms show it is absolutely necessary for machine learning engineers to consider several things about the dataset they are using to train their models. They should consider the source of the data, how the data was collected, and how relevant is the data today. The data collected to train the predictive police algorithm for Chicago was likely influenced by prejudice and systemic racism that has been affecting America for a very long time. As difficult as it can be to identify, it is very important that these factors be considered.

Reference:
Ferguson, J. M. (2020). Advisory Concerning the Chicago Police Department's Predictive Risk Models (United States, City of Chicago, Office of Inspector General).
