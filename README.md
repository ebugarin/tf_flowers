# tf_flowers

# **Flowers Image Classifier**

Code with Linear Regresion and Logistic Regresion

## **Technology Used**
* Machine Learning
* Deep Learning
* Transfer Learning

## **Tools Used**

* NumPy 
* Tensorflow
* Scikit-Learn
* Pillow 

## **API Reference**
**[TensorFlow](https://linktodocumentation)**

**[Scikit-learn](https://scikit-learn.org/stable/modules/classes.html)**

**[Pillow](https://pillow.readthedocs.io/en/stable/)**

**[Matplotlib](https://matplotlib.org/stable/index.html)**

**[NumPy](https://numpy.org/doc/stable/reference/index.html)**

## **Dependency Installation**
If you are running it on Google Colab then no need to set up anything as Google Colab has all the dependencies installed. You can skip this part if you are on Google Colab otherwise follow these instructions to install everything properly.
#### **Prerequisites**
Python 3.8
pip 19.0 or later
* ### Windows
```bash
  pip install numpy
  pip install matplotlib
  pip install -U scikit-learn
  pip install Pillow
  pip install --user --upgrade tensorflow
```    

* ### Linux
```bash
  $ pip3 install numpy
  $ pip3 install matplotlib
  $ pip3 install -U scikit-learn
  $ pip3 install Pillow
  $ pip3 install --user --upgrade tensorflow
```    
## **Prepare Dataset**
Dataset is freely available and can be downloaded by running Jupyter Notebook cells. It will download the dataset and extract it in correct directory.
To downlaod dataset [Click Here](https://storage.googleapis.com/download.tensorflow.org/example_images)

## **Training Process**
Training is very simple just run all the cells of Notebook and it will train all the models and logging will be printed for every cell in output.

## **GPU Support**
 GPU Support is avaible for TensorFlow only. In Google colab GPU support is already configured you have to just change the runtime environment to utilize GPU.
### **Setup GPU support on Google Colab**
```
Click on Runtime tab > Change runtime type > select GPU
```
### **GPU support for local machine**
To setup GPU support refer to the
[Nvidia GPU Drivers](https://www.nvidia.com/download/index.aspx?lang=en-us)  and 
[TensorFlow GPU Support](https://www.tensorflow.org/install/gpu)  page

## **Note**
This script does not need any arguements. 
There may arise some warnings but can be safely ignored.
If you don't have GPU on you device it will not raise any errors but a warning and script will use CPU by default.
