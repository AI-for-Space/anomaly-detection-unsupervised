# anomaly-detection-unsupervised

In this repository you can find the master's thesis carried out by Damián Mateos García and directed by Cesar Augusto Guzmán Álvarez at the International University of Valencia (VIU).

The work is written in Spanish and the repository contains the document where it is written and the code in ipynb format with which it was made.

The summary of the work is as follows:

### Abstract

The Interplanetary Magnetic Field (IMF) is a vector that represents the magnetic field 
coming from the Sun and carried by the solar wind between the planets. Its existence 
influences space missions, communication with satellites and interaction with the Earth's 
magnetic field.


Knowing and monitoring the behavior of this magnitude helps to increase the existing 
knowledge about the Solar System and the interactions between the Sun and the 
planets. Also, detecting behavioral abnormalities of this magnitude is useful for studying 
them in greater detail and finding a cause. This detection of anomalous values can also 
serve as an alert for missions that may be affected by certain magnitude values.


The main objective of this Master's Thesis is the application of unsupervised learning 
techniques to monitor the temporal evolution of the Interplanetary Magnetic Field and 
detect outliers that mean geomagnetic storms.


Different machine learning techniques have been used to detect anomalies such as 
variational AutoEncoders, Isolation Forest, Empirical-Cumulative Outlier Detection or an 
ensemble algorithm called Large-Scale Unsupervised Outlier Detection.


The performance of all these algorithms is compared in different aspects such as the 
training and prediction time, the number of hyperparameters they have and the outliers 
detected. Being in an unsupervised environment without real labels, the most 
widespread statistical definition of outlier is used to have reference labels. Online 
machine learning techniques are also applied, simulating the arrival of data in real time 
and the adaptability in a windowed model training process.


Finally, the conclusions obtained with the completion of the work and future possibilities 
to be explored to improve and advance with what has been started in this Master's Thesis 
are presented.
