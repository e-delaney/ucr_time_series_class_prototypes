# ucr_time_series_class_prototypes
Simple code to quickly retrieve class prototypes for any dataset in the UCR archive!

In this notebook we generate class prototypes for any dataset in the UCR archive 😎. We also make use of handy functionality from tslearn and sklearn_extra. Class prototypes are instances that are maximally representative of a class. They are a popular tool for XAI and can also be used for classification purposes. There are many intricate and clever ways of retrieving class prototypes. However, as a simple baseline we fit k-medoids clustering on each class and retrieve the centroid. This class centroid acts as the prototype. This code can easily be tailored to work for image or tabular data and could also be extended to multivariate time series data. We can also visualize the prototypes❗

The next thing to do is to compute prototypes using k-means with dynamic barycenter averaging. 
