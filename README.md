# Anomaly_Detection
This code is about Log Anomaly Detection

Keeping a record of events that happen in a computer system, such as issues, faults, or just details on current processes, is known as logging in computing. These occurrences might take place in other programme or the operating system. For each such incident, a message or log entry is kept. Log Anomaly Detection is the simple process of software that uses machine learning to find anomalies in logs.

Anything that deviates from what is typically considered to be normal—an exception—is an anomaly. Anomaly in software engineering is defined as the occurrence of unusual or unexpected events that don't fit into the usual patterns and are therefore suspicious.

Each key in the training dataset is a single software log, and the corresponding value is the label for that log. The training dataset is in the JSON format. Logs have the labels "abnormal" and "normal" on them. The testing dataset has two columns in CSV format, one for a unique ID and the other for a software log. Train a machine learning model on the provided training data in order to determine if a given log in the testing data is abnormal or normal.

Files:-

train.json - the training dataset(https://drive.google.com/file/d/1LJrDPxxfmmLZrUa_S_oAppwbtUnoPqq6/view?usp=share_link)


test.csv - the test dataset
