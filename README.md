# prediction-of-sleep-Disorder-using-pyspark-Framework

🔬 Prediction of Sleep Disorders Using Distributed Deep Learning in PySpark
This project presents a scalable, distributed deep learning framework for predicting sleep disorders such as Insomnia and Sleep Apnea using the Sleep Health and Lifestyle Dataset. Implemented in Apache PySpark, this system leverages large-scale data processing capabilities to train and evaluate ResNet18, DenseNet121, and Deep Neural Network (DNN) models efficiently.

🧠 Key Features
📊 Big Data Processing using Apache Spark for high-volume sleep health data.

🧬 Deep Learning Models: ResNet18, DenseNet121, and DNNs for multiclass classification.

⚙️ Distributed Training to speed up model training and improve scalability.

🛌 Real-world Sleep Disorder Prediction (Insomnia, Sleep Apnea, and Healthy Sleep).

📈 Performance Evaluation: Accuracy, Sensitivity, and Specificity compared between Spark and non-Spark implementations.

🧰 Technologies Used
Apache Spark (PySpark)

Python

TensorFlow/Keras (for deep learning model integration)

Pandas, NumPy (data manipulation)

Matplotlib/Seaborn (for evaluation and plotting)

📁 Dataset
Sleep Health and Lifestyle Dataset (synthetic data from Kaggle)

Features include: Age, BMI, Blood Pressure, Heart Rate, Sleep Duration, Stress Level, Physical Activity, and more.

📊 Model Results
Model	With Spark	Without Spark
ResNet18	90%	83%
DenseNet121	89%	83%
DNN	85%	84%

🚀 How to Run
Clone this repository.

Install dependencies from requirements.txt.

Start a PySpark session.

Run the model scripts located in the models/ directory.

Evaluate predictions and visualize results.

📌 Conclusion
This project demonstrates how integrating deep learning with big data technologies enables high-accuracy and scalable sleep disorder prediction systems, paving the way for real-time, cost-effective, and non-invasive screening.
