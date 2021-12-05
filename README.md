# Seizure Detection
<p align="justify">
The main field of work of this thesis is the detection of seizures using machine learning methods. The data we used came from scalp electroencephalograms (EEGs). This is the 
CHB-MIT database, which is available for free, from the <a href="https://archive.physionet.org/pn6/chbmit/">PhysioNet platform</a>. In the context of the implementation, the whole 
process of data management was examined from their download, the extraction of characteristics (mean, variance, skewness, kurtosis, standard deviation, median, zero crossings, 
root mean square, peak to peak, sample entropy, power via PSD in the delta, theta, alpha, beta, gamma frequencies, maximum correlation) from them, their normalization (z-score), 
the reduction of dimensions (PCA) by preserving their inherent information, the balancing of epileptic and non-epileptic samples (Cluster Centroids, ADASYN) to training, optimization 
(grid search) and classifier implementation (SVM, kNN, Naive Bayes, Decision Trees, Random Forest, LDA, Logistic Regression, Neural Network with LSTM), their evaluation (accuracy, 
sensitivity/recall, specificity, precision, F1 score, Matthews correlation coefficient, Cohen's Kappa coefficient) and comparison of results. Three different experiments are 
performed either by using the measurements of all the electrodes or part of them. The main difference of our method in relation to the bibliography is that the results of the 
generalization of the methods are examined in contrast to the focused ones on each patient that is usually encountered. All of the above is done using Python, which is the most 
popular of machine learning applications, and the Jupyter platform. <br/> 
My thesis is available <a href="https://pergamos.lib.uoa.gr/uoa/dl/object/2932363">here</a>. </p>
