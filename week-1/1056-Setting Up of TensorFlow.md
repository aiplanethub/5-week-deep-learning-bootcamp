TIP #0: If you don't have context about Google Colab & Jupyter notebook, please refer to optional slides about related topics under Week 0.

## Learning Objectives

* CPU, GPU, and TPU
* GPU Packages for Deep Learning
* Setting up TensorFlow
* Importing TensorFlow and checking its version\


**TIP:** You DON'T need to memorize the below jargons!

### CPUs

* The **CPU** or Central Processing Unit is the primary component of a computer that processes instructions. It's called the brain of the computer.

### GPUs

* **GPU** stands for the graphics processing unit. You'll also see GPUs being referred to as **graphics cards** or **video cards**. Every PC uses a GPU to render images, video, and 2D or 3D animations for display. A GPU performs quick math calculations and frees up the CPU to do other things.
* The introduction of GPUs led to the rise of gaming industries and industries that provide high-quality visuals. GPUs are not only used in machine learning-related work but are also highly useful for content creators, digital artists, and gamers.
* GPUs play a crucial role while training Deep Learning models. To learn what makes them so important, we would recommend you to go through a very interesting article below that explains why GPUs are necessary for training Deep Learning models:
* [Why are GPUs necessary for training Deep Learning models?](https://www.analyticsvidhya.com/blog/2017/05/gpus-necessary-for-deep-learning/)

### TPUs

* Tensor Processing Unit, i.e., **TPU**, is a designated architecture for DL/ML computation designed by Google. It's not a generic processor; only Tensorflow models can run on it.







![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_243a7ce7dd614c6daa7cb2d6d31d27e9.png)







* TPU outperforms CPU and GPU for various Deep Learning models in terms of predictions per second. Source: Sato et al. 2017.
* If you wish to know more about TPUs, you can read the below article: [https://cloud.google.com/tpu](https://cloud.google.com/tpu)

### Why GPU and TPU?

* CPU can be used to train the model where data is relatively small. The GPUs were introduced as the CPU was slower when dealing with data that required huge computations.
* In a nutshell, GPUs and TPUs are used to reduce the computation time to train eﬃciently a deep learning model when large datasets need to be processed.

### What GPU Packages are required for DL?

For performing Deep Learning operations, 2 GPU Packages are configured while installing TensorFlow. These are:

**CUDA:**

* CUDA is NVIDIA's language/API for programming on the graphics card. It is one of the easiest ways to write high-performance programs run on the GPU.
* You can accelerate deep learning and other compute-intensive apps by taking advantage of CUDA and the parallel processing power of GPUs

**cuDNN:**&#x20;

* The NVIDIA CUDA Deep Neural Network library (cuDNN) is a GPU-accelerated library for deep neural networks.
* It is built using CUDA and provides GPU accelerated functionality and highly tuned implementations for common operations in deep neural nets.
* Deep learning researchers and framework developers worldwide rely on cuDNN for high-performance GPU acceleration. It allows them to focus on training neural networks and developing software applications rather than spending time on low-level GPU performance tuning.

## Setting up Tensorflow

### Option 1: Google Colab (Virtual Environment - No installation required)

* Google oﬀers Google Colab notebooks (also called the online version of Jupyter notebook) that are an **easy-to-use and interactive data science environment.**
  * Not just that, Google Colab oﬀers you up to 12 GB ram/GPU/TPU, etc. **for free** and 100 GB storage.
  * So, you don't need to worry about installing a bulky python local application on your laptop/computer
* **Google colab registration:** [https://colab.research.google.com/](https://colab.research.google.com)
* Colab gives you a decent GPU for free, which you can continuously run for 12 hours. For most data science folks, this is suﬃcient to meet their computation needs.
* Google Colab gives us three types of runtime for our notebooks:
  * CPUs,
  * GPUs, and
  * TPUs
* **Why GPU/TPU?** In a nutshell, GPUs and TPUs are used for reducing the computation time to train eﬃciently a deep learning model when large datasets need to be processed.

**TPUs**

* Tensor Processing Units, i.e., TPUs, have been recently added to Google Colab, making it even more attractive for quick-and-dirty machine learning projects when your local processing units are not fast enough.

**Choosing the GPU or TPU Option**

* The ability to choose diﬀerent types of runtimes is what makes Colab so popular and powerful. Here are the steps to change the runtime of your notebook:
* **STEP 1:** Click' Runtime' on the top menu and select 'Change Runtime Type':












![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_bd3f6ddb7aae4ae88b07631f72052720.png)













* **Step 2:** Here, you can change the runtime according to your need:
  * To install Tensorflow on Colab
  * Open your Colab notebook
  * Type the following command: `!pip install tensorflow`
* Once the installation is done, run the below command to import tensorflow: `import tensorflow as tf`

### Option 2: Installing on Device

To install Tensorflow on device

* Open your Jupyter notebook
* Type the following command: **`!pip install tensorflow`**
* Once the installation is done, run the below command to import tensorflow: **`import tensorflow as tf`**














<iframe width="100%" height="315" src="https://youtube.com/embed/VC-EliTgMEM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>















## Checking the version of TensorFlow

* Open a Jupyter Notebook/Google Colab
* In a cell, type and execute the following command:








![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_3f37a8a4107c49709d8850e77d8768ca.png)








* Make sure the displayed version starts with 2, i.e., ensure Tensorflow 2 has been installed. If not, you can upgrade Tensorflow: Pip upgrade: [https://stackoverflow.com/a/47342614](https://stackoverflow.com/a/47342614)\
  Conda upgrade: conda upgrade tensorflow-gpu
* Google Colab uses TensorFlow 2 by default.

### Additional Resources on Installation!

* [Install Tensorflow GPU on Windows 10 with CUDA and cuDNN](https://www.youtube.com/watch?v=xQVOaTUm9lM)\
  **Intermediate/advanced Learners can explore this option**. For rest, we can gradually get there whenever required. For the moment, you can simply go with Google Colab or the device installation mentioned earlier.