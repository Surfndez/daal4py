##########
Algorithms
##########

Classification
--------------
See also `Intel DAAL Classification
<https://software.intel.com/en-us/daal-programming-guide-classification>`__.

Decision Forest Classification
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Classification Decision Forest <https://software.intel.com/en-us/daal-programming-guide-decision-forest-2>`__

Examples:

- `Single-Process Decision Forest Classification
  <https://github.com/IntelPython/daal4py/blob/master/examples/decision_forest_classification_batch.py>`__

.. autoclass:: daal4py.decision_forest_classification_training
   :members: compute
.. autoclass:: daal4py.decision_forest_classification_training_result
   :members:
.. autoclass:: daal4py.decision_forest_classification_prediction
   :members: compute
.. autoclass:: daal4py.classifier_prediction_result
   :members:
.. autoclass:: daal4py.decision_forest_classification_model
   :members:

Decision Tree Classification
^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Classification Decision Tree <https://software.intel.com/en-us/daal-programming-guide-decision-tree-2>`__

Examples:

- `Single-Process Decision Tree Classification
  <https://github.com/IntelPython/daal4py/blob/master/examples/decision_tree_classification_batch.py>`__

.. autoclass:: daal4py.decision_tree_classification_training
   :members: compute
.. autoclass:: daal4py.decision_tree_classification_training_result
   :members:
.. autoclass:: daal4py.decision_tree_classification_prediction
   :members: compute
.. autoclass:: daal4py.classifier_prediction_result
   :members:
.. autoclass:: daal4py.decision_tree_classification_model
   :members:

Gradient Boosted Classification
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Classification Gradient Boosted Tree <https://software.intel.com/en-us/daal-programming-guide-gradient-boosted-trees-2>`__

Examples:

- `Single-Process Gradient Boosted Classification
  <https://github.com/IntelPython/daal4py/blob/master/examples/gradient_boosted_classification_batch.py>`__

.. autoclass:: daal4py.gbt_classification_training
   :members: compute
.. autoclass:: daal4py.gbt_classification_training_result
   :members:
.. autoclass:: daal4py.gbt_classification_prediction
   :members: compute
.. autoclass:: daal4py.classifier_prediction_result
   :members:
.. autoclass:: daal4py.gbt_classification_model
   :members:

k-Nearest Neighbors (kNN)
^^^^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL k-Nearest Neighbors (kNN)
<https://software.intel.com/en-us/daal-programming-guide-k-nearest-neighbors-knn-classifier>`__

Examples:

- `Single-Process kNN
  <https://github.com/IntelPython/daal4py/blob/master/examples/kdtree_knn_classification_batch.py>`__

.. autoclass:: daal4py.kdtree_knn_classification_training
   :members: compute
.. autoclass:: daal4py.kdtree_knn_classification_training_result
   :members:
.. autoclass:: daal4py.kdtree_knn_classification_prediction
   :members: compute
.. autoclass:: daal4py.classifier_prediction_result
   :members:
.. autoclass:: daal4py.kdtree_knn_classification_model
   :members:

..
    Remove this line, line above and indent below when algorithm will be added
    AdaBoost Classification
    ^^^^^^^^^^^^^^^^^^^^^^^
    Detailed description of parameters and semantics are described in
    `Intel DAAL Classification AdaBoost <https://software.intel.com/en-us/daal-programming-guide-adaboost-classifier>`__

    Examples:

    - `Single-Process AdaBoost Classification
      <https://github.com/IntelPython/daal4py/blob/master/examples/adaboost_batch.py>`__

    .. autoclass:: daal4py.adaboost_training
       :members: compute
    .. autoclass:: daal4py.adaboost_training_result
       :members:
    .. autoclass:: daal4py.adaboost_prediction
       :members: compute
    .. autoclass:: daal4py.classifier_prediction_result
       :members:
    .. autoclass:: daal4py.adaboost_model
       :members:

..
    Remove this line, line above and indent below when algorithm will be added
    BrownBoost Classification
    ^^^^^^^^^^^^^^^^^^^^^^^^^
    Detailed description of parameters and semantics are described in
    `Intel DAAL Classification BrownBoost <https://software.intel.com/en-us/daal-programming-guide-brownboost-classifier>`__

    Examples:

    - `Single-Process BrownBoost Classification
      <https://github.com/IntelPython/daal4py/blob/master/examples/brownboost_batch.py>`__

    .. autoclass:: daal4py.brownboost_training
       :members: compute
    .. autoclass:: daal4py.brownboost_training_result
       :members:
    .. autoclass:: daal4py.brownboost_prediction
       :members: compute
    .. autoclass:: daal4py.classifier_prediction_result
       :members:
    .. autoclass:: daal4py.brownboost_model
       :members:

..
    Remove this line, line above and indent below when algorithm will be added
    LogitBoost Classification
    ^^^^^^^^^^^^^^^^^^^^^^^^^
    Detailed description of parameters and semantics are described in
    `Intel DAAL Classification LogitBoost <https://software.intel.com/en-us/daal-programming-guide-logitboost-classifier>`__

    Examples:

    - `Single-Process LogitBoost Classification
      <https://github.com/IntelPython/daal4py/blob/master/examples/logitboost_batch.py>`__

    .. autoclass:: daal4py.logitboost_training
       :members: compute
    .. autoclass:: daal4py.logitboost_training_result
       :members:
    .. autoclass:: daal4py.logitboost_prediction
       :members: compute
    .. autoclass:: daal4py.classifier_prediction_result
       :members:
    .. autoclass:: daal4py.logitboost_model
       :members:

..
    Remove this line, line above and indent below when algorithm will be added
    Stump Weak Learner Classification
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
    Detailed description of parameters and semantics are described in
    `Intel DAAL Classification Weak Learner Stump <https://software.intel.com/en-us/daal-programming-guide-stump-weak-learner-classifier>`__

    Examples:

    - `Single-Process Stump Weak Learner Classification
      <https://github.com/IntelPython/daal4py/blob/master/examples/stump_classification_batch.py>`__

    .. autoclass:: daal4py.stump_classification_training
       :members: compute
    .. autoclass:: daal4py.stump_classification_training_result
       :members:
    .. autoclass:: daal4py.stump_classification_prediction
       :members: compute
    .. autoclass:: daal4py.classifier_prediction_result
       :members:
    .. autoclass:: daal4py.stump_classification_model
       :members:

Multinomial Naive Bayes
^^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Naive Bayes
<https://software.intel.com/en-us/daal-programming-guide-naive-bayes-classifier>`__

Examples:

- `Single-Process Naive Bayes <https://github.com/IntelPython/daal4py/blob/master/examples/naive_bayes_batch.py>`__
- `Streaming Naive Bayes <https://github.com/IntelPython/daal4py/blob/master/examples/naive_bayes_streaming.py>`__
- `Multi-Process Naive Bayes <https://github.com/IntelPython/daal4py/blob/master/examples/naive_bayes_spmd.py>`__

.. autoclass:: daal4py.multinomial_naive_bayes_training
   :members: compute
.. autoclass:: daal4py.multinomial_naive_bayes_training_result
   :members:
.. autoclass:: daal4py.multinomial_naive_bayes_prediction
   :members: compute
.. autoclass:: daal4py.classifier_prediction_result
   :members:
.. autoclass:: daal4py.multinomial_naive_bayes_model
   :members:

Support Vector Machine (SVM)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL SVM <https://software.intel.com/en-us/daal-programming-guide-support-vector-machine-classifier>`__

Examples:

- `Single-Process SVM
  <https://github.com/IntelPython/daal4py/blob/master/examples/svm_batch.py>`__

.. autoclass:: daal4py.svm_training
   :members: compute
.. autoclass:: daal4py.svm_training_result
   :members:
.. autoclass:: daal4py.svm_prediction
   :members: compute
.. autoclass:: daal4py.classifier_prediction_result
   :members:
.. autoclass:: daal4py.svm_model
   :members:

Logistic Regression
^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Logistic Regression <https://software.intel.com/en-us/daal-programming-guide-logistic-regression>`__

Examples:

- `Single-Process Binary Class Logistic Regression
  <https://github.com/IntelPython/daal4py/blob/master/examples/log_reg_binary_dense_batch.py>`__
- `Single-Process Logistic Regression
  <https://github.com/IntelPython/daal4py/blob/master/examples/log_reg_dense_batch.py>`__

.. autoclass:: daal4py.logistic_regression_training
   :members: compute
.. autoclass:: daal4py.logistic_regression_training_result
   :members:
.. autoclass:: daal4py.logistic_regression_prediction
   :members: compute
.. autoclass:: daal4py.classifier_prediction_result
   :members:
.. autoclass:: daal4py.logistic_regression_model
   :members:

Regression
----------
See also `Intel DAAL Regression
<https://software.intel.com/en-us/daal-programming-guide-regression>`__.

Decision Forest Regression
^^^^^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Regression Decision Forest <https://software.intel.com/en-us/daal-programming-guide-decision-forest-1>`__

Examples:

- `Single-Process Decision Forest Regression
  <https://github.com/IntelPython/daal4py/blob/master/examples/decision_forest_regression_batch.py>`__

.. autoclass:: daal4py.decision_forest_regression_training
   :members: compute
.. autoclass:: daal4py.decision_forest_regression_training_result
   :members:
.. autoclass:: daal4py.decision_forest_regression_prediction
   :members: compute
.. autoclass:: daal4py.decision_forest_regression_prediction_result
   :members:
.. autoclass:: daal4py.decision_forest_regression_model
   :members:

Decision Tree Regression
^^^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Regression Decision Tree <https://software.intel.com/en-us/daal-programming-guide-decision-tree-1>`__

Examples:

- `Single-Process Decision Tree Regression
  <https://github.com/IntelPython/daal4py/blob/master/examples/decision_tree_regression_batch.py>`__

.. autoclass:: daal4py.decision_tree_regression_training
   :members: compute
.. autoclass:: daal4py.decision_tree_regression_training_result
   :members:
.. autoclass:: daal4py.decision_tree_regression_prediction
   :members: compute
.. autoclass:: daal4py.decision_tree_regression_prediction_result
   :members:
.. autoclass:: daal4py.decision_tree_regression_model
   :members:

Gradient Boosted Regression
^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Regression Gradient Boosted Tree <https://software.intel.com/en-us/daal-programming-guide-gradient-boosted-trees-1>`__

Examples:

- `Single-Process Boosted Regression Regression
  <https://github.com/IntelPython/daal4py/blob/master/examples/gradient_boosted_regression_batch.py>`__

.. autoclass:: daal4py.gbt_regression_training
   :members: compute
.. autoclass:: daal4py.gbt_regression_training_result
   :members:
.. autoclass:: daal4py.gbt_regression_prediction
   :members: compute
.. autoclass:: daal4py.gbt_regression_prediction_result
   :members:
.. autoclass:: daal4py.gbt_regression_model
   :members:

Linear Regression
^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Linear and Ridge Regression <https://software.intel.com/en-us/daal-programming-guide-linear-and-ridge-regressions-computation>`__

Examples:

- `Single-Process Linear Regression <https://github.com/IntelPython/daal4py/blob/master/examples/linear_regression_batch.py>`__
- `Streaming Linear Regression <https://github.com/IntelPython/daal4py/blob/master/examples/linear_regression_streaming.py>`__
- `Multi-Process Linear Regression <https://github.com/IntelPython/daal4py/blob/master/examples/linear_regression_spmd.py>`__

.. autoclass:: daal4py.linear_regression_training
   :members: compute
.. autoclass:: daal4py.linear_regression_training_result
   :members:
.. autoclass:: daal4py.linear_regression_prediction
   :members: compute
.. autoclass:: daal4py.linear_regression_prediction_result
   :members:
.. autoclass:: daal4py.linear_regression_model
   :members:

Ridge Regression
^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Linear and Ridge Regression <https://software.intel.com/en-us/daal-programming-guide-linear-and-ridge-regressions-computation>`__

Examples:

- `Single-Process Ridge Regression <https://github.com/IntelPython/daal4py/blob/master/examples/ridge_regression_batch.py>`__
- `Streaming Ridge Regression <https://github.com/IntelPython/daal4py/blob/master/examples/ridge_regression_streaming.py>`__
- `Multi-Process Ridge Regression <https://github.com/IntelPython/daal4py/blob/master/examples/ridge_regression_spmd.py>`__

.. autoclass:: daal4py.ridge_regression_training
   :members: compute
.. autoclass:: daal4py.ridge_regression_training_result
   :members:
.. autoclass:: daal4py.ridge_regression_prediction
   :members: compute
.. autoclass:: daal4py.ridge_regression_prediction_result
   :members:
.. autoclass:: daal4py.ridge_regression_model
   :members:

..
    Remove this line, line above and indent below when algorithm will be added
    Stump Weak Learner Regression
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
    Detailed description of parameters and semantics are described in
    `Intel DAAL Regression Weak Learner Stump <https://software.intel.com/en-us/daal-programming-guide-stump-weak-learner-classifier>`__

    Examples:

    - `Single-Process Stump Weak Learner Regression
      <https://github.com/IntelPython/daal4py/blob/master/examples/stump_regression_batch.py>`__

    .. autoclass:: daal4py.stump_regression_training
       :members: compute
    .. autoclass:: daal4py.stump_regression_training_result
       :members:
    .. autoclass:: daal4py.stump_regression_prediction
       :members: compute
    .. autoclass:: daal4py.stump_regression_prediction_result
       :members:
    .. autoclass:: daal4py.stump_regression_model
       :members:

Principal Component Analysis (PCA)
----------------------------------
Detailed description of parameters and semantics are described in
`Intel DAAL PCA <https://software.intel.com/en-us/daal-programming-guide-principal-component-analysis>`__

Examples:

- `Single-Process PCA <https://github.com/IntelPython/daal4py/blob/master/examples/pca_batch.py>`__
- `Multi-Process PCA <https://github.com/IntelPython/daal4py/blob/master/examples/pca_spmd.py>`__

.. autoclass:: daal4py.pca
   :members: compute
.. autoclass:: daal4py.pca_result
   :members:

Principal Component Analysis (PCA) Transform
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL PCA Transform <https://software.intel.com/en-us/daal-programming-guide-principal-components-analysis-transform>`__

Examples:

- `Single-Process PCA Transform <https://github.com/IntelPython/daal4py/blob/master/examples/pca_transform_batch.py>`__

.. autoclass:: daal4py.pca_transform
   :members: compute
.. autoclass:: daal4py.pca_transform_result
   :members:

K-Means Clustering
------------------
Detailed description of parameters and semantics are described in
`Intel DAAL K-Means-Clustering <https://software.intel.com/en-us/daal-programming-guide-k-means-clustering>`__

Examples:

- `Single-Process K-Means <https://github.com/IntelPython/daal4py/blob/master/examples/kmeans_batch.py>`__
- `Multi-Process K-Means <https://github.com/IntelPython/daal4py/blob/master/examples/kmeans_spmd.py>`__

K-Means Initialization
^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL K-Means Initialization <https://software.intel.com/en-us/daal-programming-guide-initialization>`__

.. autoclass:: daal4py.kmeans_init
   :members: compute
.. autoclass:: daal4py.kmeans_init_result
   :members:

K-Means
^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL K-Means Computation <https://software.intel.com/en-us/daal-programming-guide-computation>`__

.. autoclass:: daal4py.kmeans
   :members: compute
.. autoclass:: daal4py.kmeans_result
   :members:

Outlier Detection
-----------------
Multivariate Outlier Detection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Multivariate Outlier Detection <https://software.intel.com/en-us/daal-programming-guide-multivariate-outlier-detection>`__

Examples:

- `Single-Process Multivariate Outlier Detection <https://github.com/IntelPython/daal4py/blob/master/examples/multivariate_outlier_batch.py>`__

.. autoclass:: daal4py.multivariate_outlier_detection
   :members: compute
.. autoclass:: daal4py.multivariate_outlier_detection_result
   :members:

Univariate Outlier Detection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Univariate Outlier Detection <https://software.intel.com/en-us/daal-programming-guide-univariate-outlier-detection>`__

Examples:

- `Single-Process Univariate Outlier Detection <https://github.com/IntelPython/daal4py/blob/master/examples/univariate_outlier_batch.py>`__

.. autoclass:: daal4py.univariate_outlier_detection
   :members: compute
.. autoclass:: daal4py.univariate_outlier_detection_result
   :members:

Multivariate Bacon Outlier Detection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Multivariate Bacon Outlier Detection <https://software.intel.com/en-us/daal-programming-guide-multivariate-bacon-outlier-detection>`__

Examples:

- `Single-Process Bacon Outlier Detection <https://github.com/IntelPython/daal4py/blob/master/examples/bacon_outlier_batch.py>`__

.. autoclass:: daal4py.bacon_outlier_detection
   :members: compute
.. autoclass:: daal4py.bacon_outlier_detection_result
   :members:

Optimization Solvers
--------------------
Objective Functions
^^^^^^^^^^^^^^^^^^^
Mean Squared Error Algorithm (MSE)
""""""""""""""""""""""""""""""""""
Detailed description of parameters and semantics are described in
`Intel DAAL MSE <https://software.intel.com/en-us/daal-programming-guide-mean-squared-error-algorithm>`__

Examples:
- `In Adagrad <https://github.com/IntelPython/daal4py/blob/master/examples/adagrad_mse_batch.py>`__
- `In LBFGS <https://github.com/IntelPython/daal4py/blob/master/examples/lbfgs_mse_batch.py>`__
- `In SGD <https://github.com/IntelPython/daal4py/blob/master/examples/sgd_mse_batch.py>`__

.. autoclass:: daal4py.optimization_solver_mse
   :members: compute, setup
.. autoclass:: daal4py.optimization_solver_mse_result
   :members:

Logistic Loss
"""""""""""""
Detailed description of parameters and semantics are described in
`Intel DAAL Logistic Loss <https://software.intel.com/en-us/daal-programming-guide-logistic-loss>`__

Examples:
- `In SGD <https://github.com/IntelPython/daal4py/blob/master/examples/sgd_logistic_loss_batch.py>`__

.. autoclass:: daal4py.optimization_solver_logistic_loss
   :members: compute, setup
.. autoclass:: daal4py.optimization_solver_logistic_loss_result
   :members:

Cross-entropy Loss
""""""""""""""""""
Detailed description of parameters and semantics are described in
`Intel DAAL Cross Entropy Loss <https://software.intel.com/en-us/daal-programming-guide-cross-entropy-loss>`__

.. autoclass:: daal4py.optimization_solver_cross_entropy_loss
   :members: compute, setup
.. autoclass:: daal4py.optimization_solver_cross_entropy_loss_result
   :members:

Iterative Solvers
^^^^^^^^^^^^^^^^^
Stochastic Gradient Descent Algorithm
"""""""""""""""""""""""""""""""""""""
Detailed description of parameters and semantics are described in
`Intel DAAL SGD <https://software.intel.com/en-us/daal-programming-guide-stochastic-gradient-descent-algorithm>`__

Examples:
- `Using Logistic Loss <https://github.com/IntelPython/daal4py/blob/master/examples/sgd_logistic_loss_batch.py>`__
- `Using MSE <https://github.com/IntelPython/daal4py//blob/master/examples/sgd_mse_batch.py>`__

.. autoclass:: daal4py.optimization_solver_sgd
   :members: compute
.. autoclass:: daal4py.optimization_solver_sgd_result
   :members:

Limited-Memory Broyden-Fletcher-Goldfarb-Shanno Algorithm
"""""""""""""""""""""""""""""""""""""""""""""""""""""""""
Detailed description of parameters and semantics are described in
`Intel DAAL LBFGS <https://software.intel.com/en-us/daal-programming-guide-limited-memory-broyden-fletcher-goldfarb-shanno-algorithm>`__

Examples:
- `Using MSE <https://github.com/IntelPython/daal4py/blob/master/examples/lbfgs_mse_batch.py>`__

.. autoclass:: daal4py.optimization_solver_lbfgs
   :members: compute
.. autoclass:: daal4py.optimization_solver_lbfgs_result
   :members:

Adaptive Subgradient Method
"""""""""""""""""""""""""""
Detailed description of parameters and semantics are described in
`Intel DAAL AdaGrad <https://software.intel.com/en-us/daal-programming-guide-adaptive-subgradient-method>`__

Examples:
- `Using MSE <https://github.com/IntelPython/daal4py/blob/master/examples/adagrad_mse_batch.py>`__

.. autoclass:: daal4py.optimization_solver_adagrad
   :members: compute
.. autoclass:: daal4py.optimization_solver_adagrad_result
   :members:

Stochastic Average Gradient Descent
"""""""""""""""""""""""""""""""""""
Detailed description of parameters and semantics are described in
`Intel DAAL Stochastic Average Gradient Descent SAGA <https://software.intel.com/en-us/daal-programming-guide-stochastic-average-gradient-descent>`__

Examples:
- `Single Proces saga-logistc_loss <https://github.com/IntelPython/daal4py/blob/master/examples/saga_batch.py>`__

.. autoclass:: daal4py.optimization_solver_saga
   :members: compute
.. autoclass:: daal4py.optimization_solver_saga_result
   :members:

Distances
---------
Cosine Distance Matrix
^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Cosine Distance <https://software.intel.com/en-us/daal-programming-guide-cosine-distance-matrix>`__

Examples:

- `Single-Process Cosine Distance <https://github.com/IntelPython/daal4py/blob/master/examples/cosine_distance_batch.py>`__

.. autoclass:: daal4py.cosine_distance
   :members: compute
.. autoclass:: daal4py.cosine_distance_result
   :members:

Correlation Distance Matrix
^^^^^^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Correlation Distance <https://software.intel.com/en-us/daal-programming-guide-correlation-distance-matrix>`__

Examples:

- `Single-Process Correlation Distance <https://github.com/IntelPython/daal4py/blob/master/examples/correlation_distance_batch.py>`__

.. autoclass:: daal4py.correlation_distance
   :members: compute
.. autoclass:: daal4py.correlation_distance_result
   :members:

Expectation-Maximization (EM)
-----------------------------
Detailed description of parameters and semantics are described in
`Intel DAAL Expectation-Maximization <https://software.intel.com/en-us/daal-programming-guide-expectation-maximization>`__

Initialization for the Gaussian Mixture Model
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Expectation-Maximization Initialization <https://software.intel.com/en-us/daal-programming-guide-initialization-1>`__

Examples:

- `Single-Process Expectation-Maximization <https://github.com/IntelPython/daal4py/blob/master/examples/em_gmm_batch.py>`__

.. autoclass:: daal4py.em_gmm_init
   :members: compute
.. autoclass:: daal4py.em_gmm_init_result
   :members:

EM algorithm for the Gaussian Mixture Model
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Expectation-Maximization <https://software.intel.com/en-us/daal-programming-guide-computation-1>`__

Examples:

- `Single-Process Expectation-Maximization <https://github.com/IntelPython/daal4py/blob/master/examples/em_gmm_batch.py>`__

.. autoclass:: daal4py.em_gmm
   :members: compute
.. autoclass:: daal4py.em_gmm_result
   :members:

QR Decomposition
----------------
Detailed description of parameters and semantics are described in
`Intel DAAL QR Decomposition <https://software.intel.com/en-us/daal-programming-guide-qr-decomposition>`__

QR Decomposition (without pivoting)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL QR Decomposition <https://software.intel.com/en-us/daal-programming-guide-qr-decomposition-without-pivoting>`__

Examples:

- `Single-Process QR <https://github.com/IntelPython/daal4py/blob/master/examples/qr_batch.py>`__
- `Streaming QR <https://github.com/IntelPython/daal4py/blob/master/examples/qr_streaming.py>`__

.. autoclass:: daal4py.qr
   :members: compute
.. autoclass:: daal4py.qr_result
   :members:

Pivoted QR Decomposition
^^^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Pivoted QR Decomposition <https://software.intel.com/en-us/daal-programming-guide-pivoted-qr-decomposition>`__

Examples:

- `Single-Process Pivoted QR <https://github.com/IntelPython/daal4py/blob/master/examples/pivoted_qr_batch.py>`__

.. autoclass:: daal4py.pivoted_qr
   :members: compute
.. autoclass:: daal4py.pivoted_qr_result
   :members:

Normalization
-------------
Detailed description of parameters and semantics are described in
`Intel DAAL Normalization <https://software.intel.com/en-us/daal-programming-guide-normalization>`__

Z-Score
^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Z-Score <https://software.intel.com/en-us/daal-programming-guide-z-score>`__

Examples:

- `Single-Process Z-Score Normalization <https://github.com/IntelPython/daal4py/blob/master/examples/normalization_zscore.py>`__

.. autoclass:: daal4py.normalization_zscore
   :members: compute
.. autoclass:: daal4py.normalization_zscore_result
   :members:

Min-Max
^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Min-Max <https://software.intel.com/en-us/daal-programming-guide-min-max>`__

Examples:

- `Single-Process Min-Max Normalization <https://github.com/IntelPython/daal4py/blob/master/examples/normalization_minmax.py>`__

.. autoclass:: daal4py.normalization_minmax
   :members: compute
.. autoclass:: daal4py.normalization_minmax_result
   :members:

Random Number Engines
---------------------
Detailed description of parameters and semantics are described in
`Intel DAAL Min-Max <https://software.intel.com/en-us/daal-programming-guide-engines>`__

.. autoclass:: daal4py.engines_result
   :members:

mt19937
^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL mt19937 <https://software.intel.com/en-us/daal-programming-guide-mt19937>`__

.. autoclass:: daal4py.engines_mt19937
   :members: compute
.. autoclass:: daal4py.engines_mt19937_result
   :members:

mt2203
^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL mt2203 <https://software.intel.com/en-us/daal-programming-guide-mt2203>`__

.. autoclass:: daal4py.engines_mt2203
   :members: compute
.. autoclass:: daal4py.engines_mt2203_result
   :members:

mcg59
^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL mcg59 <https://software.intel.com/en-us/daal-programming-guide-mcg59>`__

.. autoclass:: daal4py.engines_mcg59
   :members: compute
.. autoclass:: daal4py.engines_mcg59_result
   :members:

Distributions
-------------
Detailed description of parameters and semantics are described in
`Intel DAAL Absolute Value (abs) <https://software.intel.com/en-us/daal-programming-guide-distributions>`__

Bernoulli
^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Hyperbolic Tangent (tanh) <https://software.intel.com/en-us/daal-programming-guide-bernoulli>`__

Examples:

- `Single-Process tanh <https://github.com/IntelPython/daal4py/blob/master/examples/distributions_bernoulli.py>`__

.. autoclass:: daal4py.distributions_bernoulli
   :members: compute
.. autoclass:: daal4py.distributions_bernoulli_result
   :members:

Normal
^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Hyperbolic Tangent (tanh) <https://software.intel.com/en-us/daal-programming-guide-normal>`__

Examples:

- `Single-Process tanh <https://github.com/IntelPython/daal4py/blob/master/examples/distributions_normal.py>`__

.. autoclass:: daal4py.distributions_normal
   :members: compute
.. autoclass:: daal4py.distributions_normal_result
   :members:

Uniform
^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Hyperbolic Tangent (tanh) <https://software.intel.com/en-us/daal-programming-guide-uniform>`__

Examples:

- `Single-Process tanh <https://github.com/IntelPython/daal4py/blob/master/examples/distributions_uniform.py>`__

.. autoclass:: daal4py.distributions_uniform
   :members: compute
.. autoclass:: daal4py.distributions_uniform_result
   :members:

Math functions
--------------
Absolute Value (abs)
^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Absolute Value (abs) <https://software.intel.com/en-us/daal-programming-guide-absolute-value-abs>`__

Examples:

- `Single-Process abs <https://github.com/IntelPython/daal4py/blob/master/examples/math_abs.py>`__

.. autoclass:: daal4py.math_abs
   :members: compute
.. autoclass:: daal4py.math_abs_result
   :members:

Hyperbolic Tangent (tanh)
^^^^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Hyperbolic Tangent (tanh) <https://software.intel.com/en-us/daal-programming-guide-hyperbolic-tangent>`__

Examples:

- `Single-Process tanh <https://github.com/IntelPython/daal4py/blob/master/examples/math_tanh.py>`__

.. autoclass:: daal4py.math_tanh
   :members: compute
.. autoclass:: daal4py.math_tanh_result
   :members:

Logistic
^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Logistic <https://software.intel.com/en-us/daal-programming-guide-logistic>`__

Examples:

- `Single-Process logistic <https://github.com/IntelPython/daal4py/blob/master/examples/math_logistic.py>`__

.. autoclass:: daal4py.math_logistic
   :members: compute
.. autoclass:: daal4py.math_logistic_result
   :members:

Rectifier Linear Unit (ReLU)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Rectifier Linear Unit (ReLU) <https://software.intel.com/en-us/daal-programming-guide-rectifier-linear-unit-relu>`__

Examples:

- `Single-Process ReLU <https://github.com/IntelPython/daal4py/blob/master/examples/math_relu.py>`__

.. autoclass:: daal4py.math_relu
   :members: compute
.. autoclass:: daal4py.math_relu_result
   :members:

Smooth Rectifier Linear Unit (ReLU)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Smooth Rectifier Linear Unit (ReLU) <https://software.intel.com/en-us/daal-programming-guide-smooth-rectifier-linear-unit-smoothrelu>`__

Examples:

- `Single-Process SmoothReLU <https://github.com/IntelPython/daal4py/blob/master/examples/math_smoothrelu.py>`__

.. autoclass:: daal4py.math_smoothrelu
   :members: compute
.. autoclass:: daal4py.math_smoothrelu_result
   :members:

Softmax
^^^^^^^
Detailed description of parameters and semantics are described in
`Intel DAAL Softmax <https://software.intel.com/en-us/daal-programming-guide-softmax>`__

Examples:

- `Single-Process softmax <https://github.com/IntelPython/daal4py/blob/master/examples/math_softmax.py>`__

.. autoclass:: daal4py.math_softmax
   :members: compute
.. autoclass:: daal4py.math_softmax_result
   :members:

Association Rules
-----------------
Detailed description of parameters and semantics are described in
`Intel DAAL Association Rules <https://software.intel.com/en-us/daal-programming-guide-association-rules>`__

Examples:

- `Single-Process Association Rules <https://github.com/IntelPython/daal4py/blob/master/examples/association_rules_batch.py>`__

.. autoclass:: daal4py.association_rules
   :members: compute
.. autoclass:: daal4py.association_rules_result
   :members:

Cholesky Decomposition
----------------------
Detailed description of parameters and semantics are described in
`Intel DAAL Cholesky Decomposition <https://software.intel.com/en-us/daal-programming-guide-cholesky-decomposition>`__

Examples:

- `Single-Process Cholesky <https://github.com/IntelPython/daal4py/blob/master/examples/cholesky_batch.py>`__

.. autoclass:: daal4py.cholesky
   :members: compute
.. autoclass:: daal4py.cholesky_result
   :members:

Correlation and Variance-Covariance Matrices
--------------------------------------------
Detailed description of parameters and semantics are described in
`Intel DAAL Correlation and Variance-Covariance Matrices <https://software.intel.com/en-us/daal-programming-guide-correlation-and-variance-covariance-matrices>`__

Examples:

- `Single-Process Covariance <https://github.com/IntelPython/daal4py/blob/master/examples/covariance_batch.py>`__
- `Streaming Covariance <https://github.com/IntelPython/daal4py/blob/master/examples/covariance_streaming.py>`__
- `Multi-Process Covariance <https://github.com/IntelPython/daal4py/blob/master/examples/covariance_spmd.py>`__

.. autoclass:: daal4py.covariance
   :members: compute
.. autoclass:: daal4py.covariance_result
   :members:

Implicit Alternating Least Squares (implicit ALS)
-------------------------------------------------
Detailed description of parameters and semantics are described in
`Intel DAAL K-Means-Clustering <https://software.intel.com/en-us/daal-programming-guide-implicit-alternating-least-squares>`__

Examples:

- `Single-Process implicit ALS <https://github.com/IntelPython/daal4py/blob/master/examples/implicit_als_batch.py>`__

.. autoclass:: daal4py.implicit_als_training
   :members: compute
.. autoclass:: daal4py.implicit_als_training_result
   :members:
.. autoclass:: daal4py.implicit_als_model
   :members:
.. autoclass:: daal4py.implicit_als_prediction_ratings
   :members: compute
.. autoclass:: daal4py.implicit_als_prediction_ratings_result
   :members:

Moments of Low Order
--------------------
Detailed description of parameters and semantics are described in
`Intel DAAL Moments of Low Order <https://software.intel.com/en-us/daal-programming-guide-moments-of-low-order>`__

Examples:

- `Single-Process Low Order Moments <https://github.com/IntelPython/daal4py/blob/master/examples/low_order_moms_dense_batch.py>`__
- `Streaming Low Order Moments <https://github.com/IntelPython/daal4py/blob/master/examples/low_order_moms_dense_streaming.py>`__
- `Multi-Process Low Order Moments <https://github.com/IntelPython/daal4py/blob/master/examples/low_order_moms_spmd.py>`__

.. autoclass:: daal4py.low_order_moments
   :members: compute
.. autoclass:: daal4py.low_order_moments_result
   :members:

Quantiles
---------
Detailed description of parameters and semantics are described in
`Intel DAAL Quantiles <https://software.intel.com/en-us/daal-programming-guide-quantile>`__

Examples:

- `Single-Process Quantiles <https://github.com/IntelPython/daal4py/blob/master/examples/quantiles_batch.py>`__

.. autoclass:: daal4py.quantiles
   :members: compute
.. autoclass:: daal4py.quantiles_result
   :members:

Singular Value Decomposition (SVD)
----------------------------------
Detailed description of parameters and semantics are described in
`Intel DAAL SVD <https://software.intel.com/en-us/daal-programming-guide-singular-value-decomposition>`__

Examples:

- `Single-Process SVD <https://github.com/IntelPython/daal4py/blob/master/examples/svd_batch.py>`__
- `Streaming SVD <https://github.com/IntelPython/daal4py/blob/master/examples/svd_streaming.py>`__
- `Multi-Process SVD <https://github.com/IntelPython/daal4py/blob/master/examples/svd_spmd.py>`__

.. autoclass:: daal4py.svd
   :members: compute
.. autoclass:: daal4py.svd_result
   :members:

Sorting
-------
Detailed description of parameters and semantics are described in
`Intel DAAL sorting <https://software.intel.com/en-us/daal-programming-guide-sorting>`__

Examples:

- `Single-Process Sorting <https://github.com/IntelPython/daal4py/blob/master/examples/sorting_batch.py>`__

.. autoclass:: daal4py.sorting
   :members: compute
.. autoclass:: daal4py.sorting_result
   :members:

Trees
-----
.. autofunction:: daal4py.getTreeState

Examples:

- `Decision Forest Regression <https://github.com/IntelPython/daal4py/blob/master/examples/decision_forest_regression_traverse_batch.py>`__
- `Decision Forest Classification <https://github.com/IntelPython/daal4py/blob/master/examples/decision_forest_classification_traverse_batch.py>`__
- `Decision Tree Regression <https://github.com/IntelPython/daal4py/blob/master/examples/decision_tree_regression_traverse_batch.py>`__
- `Decision Tree Classification <https://github.com/IntelPython/daal4py/blob/master/examples/decision_tree_classification_traverse_batch.py>`__
- `Gradient Boosted Trees Regression <https://github.com/IntelPython/daal4py/blob/master/examples/gradient_boosted_regression_traverse_batch.py>`__
- `Gradient Boosted Trees Classification <https://github.com/IntelPython/daal4py/blob/master/examples/gradient_boosted_classification_traverse_batch.py>`__
