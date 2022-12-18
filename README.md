# CSE D 516 - Scalable Data Systems and Algorithms - Final Project

This project presents a benchmarking study of image processing on Apache Spark. The study focuses on the performance of image processing algorithms on Apache Spark, and compares the run time as the number of workers are increased in the cluster. The datasets used in the study includes COCO dataset. The algorithms tested include gray scale conversion of RGB images, followed by taking Laplace transform of gray scale images, data augmentation and CNN feature extraction (ResNet-18). The results of the study show that Apache Spark is a suitable platform for image processing and makes the computations very fast.

You can view the project report [here](project_final_report.pdf).

## Benchmarking Results
![exp 1](images/Time%20vs%20Number%20of%20Workers%20-%20Gray%20Scale%20%2B%20Laplace%20Transform.png)

![exp 2](images/Time%20taken%20(in%20mins)%20vs.%20Number%20of%20workers%20used_%20-%20Data%20Augmentation.png)

![exp 3.1](images/Time%20taken%20(in%20mins)%20vs%20no%20of%20workers_no%20of%20partitions%20%3D%204x%20no%20of%20cores%2C%20batch_size%20%3D%2016%20(1).png)

![exp 3.2](images/Time%20taken%20(in%20mins)%20vs.%20batch%20size%20_no%20of%20workers%20%3D%2016%20(64%20cores)%2C%20no%20of%20partitions%20%3D%20256.png)

![exp 3.3](images/Time%20taken%20(in%20mins)%20vs.%20Number%20of%20partitions%20_no%20of%20workers%20%3D%2016%20(64%20cores)%2C%20batch_size%20%3D%2016.png)


