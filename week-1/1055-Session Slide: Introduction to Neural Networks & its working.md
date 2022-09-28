### **Why Deep Learning?**






![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_a5880164c5104f399a486f664fa9a978.png)







* With increase in data, there is increase in the performance of the algorithm.
* The same is not true for other Machine learning algorithms, as they reach a plateau after a certain amount of data is provided
* Deep Learning is not a new technique, it has been around for decades, but it has only gained popularity in the last 15 years
* **Reason Being- Enormous increase in availability of data.**
* **Note:** As shown in the graph the performance plateau holds true only in comparison to older learning algorithms. And recent advancements in SOTA models such as XGBoost and LightGBM are equivalent to Deep Learning and have proven to be effective.

### **Brain Neurons**

* In brain neurons, signal is transmitted from one neuron to another till it reaches the nerve endings.







![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_07983c4002b44c4ba0d0f6c36bc25571.png)







* **SYNAPSE**: The transfer of electric signal between two neurons

### **Neural Networks**

* As the name suggests, Neural networks (also called as Artificial Neural Networks ANN) are inspired by the neurons in the human brain.





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_bd995ebdf5ca4a649f76edfc2231acc1.png)






![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_9fcaca1befdd492586998737603c9ac4.png)







### **Perceptron- Single Layer Perceptron**

* Before we begin talking about Perceptron, let us look at a general dataset





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_b1ae7b3ba5e9419591723a19457dd963.png)






* Like a single unit in Neural Network is called Neuron, the single most basic unit in Artificial neural network is called Perceptron.
* The various features of our dataset (independent values) are given as input x1, x2, x3,.... xn.
* Each input feature is given a weight to determine how important it is.
* Perceptron makes a decision y (dependent variable) on the basis of an activation function.








![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_cc2a514c55be452daf3e99cf942beedd.png)







### **Multi Layer Perceptron**

When a perceptron that teams up with additional perceptrons, stacked in several layers, to solve complex problems.








![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_4cd208b066584fc09e1a1181a36f4549.png)





In this example, we have three layers-

* **Input layer**
* **Hidden Layer**
* **Output Layer**

### **What are Hidden Layers?**

Hidden layers constitute of all the layers in a Neural Network other than the input and the output layer - Hence the word hidden.

* Hidden layers act like a black box - the internal mechanism is hidden.
* Each layer contributes to the final output layer by applying some mathematical transformations.





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_a2f0d6f7c6994979b9bec05ee589f11b.png)






### **When is a Neural Network Called Deep?**

* **Whenever there are more than 3 layers (Input, Hidden, Output) in a Neural Network, we call it a deep Neural network.**









![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_c71a4f5614af4b66a250a062d4f6f3a9.png)








* Each hidden layer has a certain meaning for the final classification.
* Each layer helps in classifying, a certain aspect of the final output layer

### **What do hidden layers do?**

**Let us consider a facial recognition Neural Network**






![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_599eb5d9e3c34b9498e50a6ff019797e.png)







* The initial layers start small - They identify edges
* The middle layer start to identify objects - like eyes, nose, ears etc.
* The final layers start to identify the final images and hence recognise the entire face.

### **Forward and Backward Propagation**





![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_eb0f540ad5f74bf0af4cc1efb330e78a.png)






* **Forward Propagation:** Signal goes from input layers towards output layers
* **Backward Propagation:** Signal goes from output to input layers

### **Classification with Neural Networks**

Classification: **Predicting what class/group certain element belongs to.**

* Classify whether a person has a disease or not
* Classify whether a person will repay loan or not
* Classify emails as spam or not&#x20;
* Apply face recognition to identify people
* And many many many more...

### **Neural Network Working: Handwriting recognition**












<iframe width="100%" height="315" src="https://youtube.com/embed/3JQ3hYko51Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>








### **Frameworks for DL in Python**

*   **TensorFlow:**&#x20;
    * Google’s DL framework.&#x20;
    * Can also work on iOS and Android
* **Pytorch:**&#x20;
  * Operates with a dynamically updated graph. It allows you to make changes to the architecture in the process.
* **Sonnet:**
  * It is built on top of TensorFlow. Designed to create neural networks with a complex architecture by DeepMind.&#x20;
  * Mostly used to reproduce the research demonstrated in DeepMind’s papers with greater ease than Keras, since DeepMind will be using Sonnet themselves.

**Let’s start working on deep learning techniques!**