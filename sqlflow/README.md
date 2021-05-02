## SQLFlow

Maintainer: [@terrytangyuan](https://github.com/terrytangyuan)
Repository: [sql-machine-learning/sqlflow](https://github.com/sql-machine-learning/sqlflow)

SQLFlow is a compiler that compiles a SQL program to a workflow that runs on Kubernetes. The input is a SQL program that written in our extended SQL grammar to support AI jobs including training, prediction, model evaluation, model explanation, custom jobs, and mathematical programming. The output is an [Argo](https://github.com/argoproj/argo-workflows) workflow that runs on a distributed Kubernetes cluster.

SQLFlow supports various database systems like MySQL, MariaDB, [TiDB](https://pingcap.com/en/), Hive, [MaxCompute](https://www.aliyun.com/product/odps) and many  machine learning toolkits like [TensorFlow](https://github.com/tensorflow/tensorflow), [Keras](https://keras.io/), [XGBoost](https://github.com/dmlc/xgboost).

More details on the design of SQLFlow are described in the paper [here](https://arxiv.org/abs/2001.06846).
