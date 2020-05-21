# CIFAR_10 
    CIFA_10 is multi-label classification problem where it has 10 classes [ airplane,automobile,bird,cat,deer,dog,frog,horse,ship,truck ], comparised of images with shape (32,32,3).
    Given code uses tensorflow and its high abstraction based keras framework to use MLP (Multiperceptron) and CNN (Convolutional Neural Network) to classifiy each category
# Installation 
To run this, install 
``` python 
pip install numpy 
pip install matplotlib
pip install tensorflow
```

Alternatively, 
```python 
pip install -r requirements.txt
```

# To Run
Use jupyter notebook or equvilent and run all cells 

# Usage 
To avoid training model, Weight are provied to load weights use as:

```python
model = get_cnn_model()
model.load_weights(filepath+'../cnn/checkpoint_100')
```
then, it can be used to further train, predict, and evaluation.
