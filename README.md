Neural Networks Project – Gesture Recognition 

Team 

Gurpreet Singh (Group Facilitator) android.gurpreet@gmail.com
Karan Prinja (Group Member) karan.prinja@rakuten.com
Problem Statement 
Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions. You want to develop a cool feature in the smart-TV that can recognize five different gestures performed by the user which will help users control the TV without using a remote. 
Each video is a sequence of 30 frames (or images).  
The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

•	Thumbs up:  Increase the volume
•	Thumbs down: Decrease the volume
•	Left swipe: 'Jump' backwards 10 seconds
•	Right swipe: 'Jump' forward 10 seconds  
•	Stop: Pause the movie


Dataset
The training data consists of a few hundred videos categorized into one of the five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames(images). These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use.


The Models
Exploring the efficacy of various deep learning models for real-time gesture recognition in smart TV applications, we delve into the characteristics and performance of eight distinct models, culminating in the selection of the optimal model that balances accuracy, generalization, and computational efficiency. 

For the specific application of gesture recognition for a smart TV using a webcam, Model 3 (Conv3D) would be the most suitable choice.    

Balance Between Accuracy and Generalization: Model 3 strikes an excellent balance with 98% training accuracy and 90% validation accuracy. This indicates not only a high degree of learning from the training dataset but also a strong ability to generalize well to new, unseen data, which is crucial for real-time gesture recognition.

Appropriate Complexity for Real-Time Processing: While Model 3 is complex enough to capture the nuances in gesture recognition (which can be quite subtle and varied), it doesn't have an excessively high number of parameters. This balance is essential for ensuring that the model can process data in real-time, a key requirement for a smooth user experience in a smart TV context.

Suitability for Video Data: Given that gesture recognition involves analyzing sequences of images (video data), the Conv3D architecture of Model 3 is well-suited for this task. It can effectively capture the spatial and temporal dynamics of gestures, which is essential for accurate recognition.

Potential for Real-World Robustness: The higher validation accuracy suggests that Model 3 will be more robust in a real-world environment, dealing effectively with the variations and unpredictability inherent in how different users might perform gestures.


In conclusion, for gesture recognition in a smart TV setup, Model 3's combination of high accuracy, good generalization, appropriate complexity, and suitability for video data makes it the optimal choice.




