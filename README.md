# KMeans Clustering on Universities
In this exercise, we will attempt to use KMeans Clustering to cluster universities into two groups, private and public.

It is important to note that we actually have the labels for this data set, but we will NOT use them for the KMeans clustering algorithm since it is an unsupervised learning algorithm.

## The Data
We will use a data frame with 777 observations on the following 18 variables:

Private: A factor with levels No and Yes indicating private or public university
Apps: Number of applications received
Accept: Number of applications accepted
Enroll: Number of new students enrolled
Top10perc: Pct. new students from top 10% of H.S. class
Top25perc: Pct. new students from top 25% of H.S. class
F.Undergrad: Number of fulltime undergraduates
P.Undergrad: Number of parttime undergraduates
Outstate: Out-of-state tuition
Room.Board: Room and board costs
Books: Estimated book costs
Personal: Estimated personal spending
PhD: Pct. of faculty with Ph.D.'s
Terminal: Pct. of faculty with terminal degree
S.F.Ratio: Student/faculty ratio
perc.alumni: Pct. alumni who donate
Expend: Instructional expenditure per student
Grad.Rate: Graduation rate
Note: We will use the labels to get an idea of how well the algorithm performed, but in a real-world setting, this would not make sense since KMeans is an unsupervised learning algorithm.

## Steps:

Import the data
Explore and preprocess the data
Perform KMeans clustering
Evaluate the model using classification report and confusion matrix (even though we have the labels, this is not a typical practice with KMeans clustering)
It is important to note that clustering is an unsupervised learning method and therefore the output is subject to interpretation.
