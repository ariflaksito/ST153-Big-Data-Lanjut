# Big Data with PySpark
All materials for Big Data &amp; Predictive Analysis Subject<br />
Faculty of Computer Science Universitas Amikom Yogayakrta

Using PySpark on Google Colab
```
!apt-get install openjdk-8-jdk-headless -qq > /dev/null
!wget -q https://archive.apache.org/dist/spark/spark-3.0.0/spark-3.0.0-bin-hadoop3.2.tgz
!tar xf spark-3.0.0-bin-hadoop3.2.tgz

!pip install -q findspark

import os
os.environ["JAVA_HOME"] = "/usr/lib/jvm/java-8-openjdk-amd64"
os.environ["SPARK_HOME"] = "/content/spark-3.0.0-bin-hadoop3.2"

!pip install pyspark
```

Install PySpark on MacOS:<br /> 
https://sparkbyexamples.com/pyspark/install-pyspark-in-jupyter-on-mac-using-homebrew/

Install PySpark on Windows:<br /> 
https://sparkbyexamples.com/pyspark/how-to-install-and-run-pyspark-on-windows/

Refferences:<br />
- https://app.datacamp.com/learn/courses/introduction-to-pyspark 
- https://app.datacamp.com/learn/courses/big-data-fundamentals-with-pyspark 
