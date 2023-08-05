# DS200.N21-Big-Data
**FINAL PROJECT: Big Data-powered Vietnamese Hate Speech Detection:A Kafka - Deep Learning Approach**

**Program language**: Python

**Environment**: Google Colab

**Content**: 

This is a coursework project aiming to integrate Big Data technology - Kafka, into a deep learning system. The project consists of two code files: "Youtube_Live_Chat" and "Kafka_Deep_Learning". In this project, the "Youtube_Live_Chat" file collects real-time comments from a specific live stream video on YouTube. Subsequently, it stores these comments in CSV files, with each file containing 10 comments.

The "Kafka_Deep_Learning" file serves the purpose of creating a pipeline that encompasses the entire process from loading data from CSV files to making predictions. The pipeline involves several steps, including loading the CSV files, preprocessing the data, writing to Kafka topics, and utilizing Kafka to stream the data for predictive modeling. The file already contains a complete pipeline code in the final cell. This cell will be initialized in a loop, so whenever a new CSV file is detected, the pipeline will automatically execute the aforementioned steps.

This project also leverages existing hate speech datasets for training the model, such as the ViHSD dataset and HSD-VLSP2019 dataset.
