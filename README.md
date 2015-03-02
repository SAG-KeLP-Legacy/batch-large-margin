batch-large-margin
=========

 [**KeLP**][kelp-site] is the Kernel-based Learning Platform developed in the [Semantic Analytics Group][sag-site] of
the [University of Roma Tor Vergata][uniroma2-site]. 

This is the batch-large-margin module of KeLP. It contains batch learning algorithms for classification and regression tasks. The following algorithms are currently implemented:

**CLASSIFICATION ALGORITHMS:**

* _LibLinearLearningAlgorithm_: it is the KeLP implementation of LibLinear (Fan '08), a linear learning algorithm for binary classification.
* _BinaryCSvmClassification_: it is the KeLP implemention of C-Support Vector Machine learning algorithm. It is a learning algorithm for binary classification and it relies on kernel functions. It is a porting of the LibSVM implementation (Chang '11)
* _BinaryNuSvmClassification_: it is the KeLP implemention of &nu;-Support Vector Machine learning algorithm. It is a learning algorithm for binary classification and it relies on kernel functions. It is a porting of the LibSVM implementation (Chang '11)
* _OneClassSvmClassification_: the KeLP implemention of One-Class Support Vector Machine learning algorithm. It is a learning algorithm for estimating the Support of a High-Dimensional Distribution and it relies on kernel functions. The model is acquired only by considering positive examples. It is useful in anomaly detection (a.k.a. novelty detection). It is a porting of the LibSVM implementation (Chang '11)
* _PegasosLearningAlgorithm_: the KeLP implementation of Primal Estimated sub-GrAdient SOlver (PEGASOS) for SVM (Singer '07). It is a linear learning algorithm for binary classification

**REGRESSION ALGORITHMS:**

* _EpsilonSvmRegression_: It implements the  &epsilon;-SVR learning algorithm discussed in (Chang '11)
  
=============

REFERENCES:

(Chang '11) Chih-Chung Chang and Chih-Jen Lin. LIBSVM: A
 library for support vector machines. ACM Transactions on Intelligent Systems and Technology, 2:27:1-27:27, 2011. Original code available at [LibSVM][libsvm-site] 
 
(Fan '08) Ron-En Fan, Kai-Wei Chang, Cho-Jui Hsieh, Xiang-Rui Wang and Chih-Jen Lin. _LIBLINEAR: A Library for Large Linear Classification_. Journal of Machine Learning Research 9(2008), 1871-1874. Original code available at [LibLinear][liblinear-site]. The original JAVA porting available at [LibLinear-java][porting-site]

(Singer '07) Y. Singer and N. Srebro. _Pegasos: Primal estimated sub-gradient solver for SVM_. In Proceeding of ICML 2007

[sag-site]: http://sag.art.uniroma2.it "SAG site"
[uniroma2-site]: http://www.uniroma2.it "University of Roma Tor Vergata"
[kelp-site]: http://sag.art.uniroma2.it/demo-software/kelp/
[liblinear-site]: http://www.csie.ntu.edu.tw/~cjlin/liblinear
[porting-site]: http://liblinear.bwaldvogel.de
[libsvm-site]: http://www.csie.ntu.edu.tw/~cjlin/libsvm/
