

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.contrib.keras.backend.zeros_like

``` python
zeros_like(
    x,
    dtype=None,
    name=None
)
```



Defined in [`tensorflow/contrib/keras/python/keras/backend.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.3/tensorflow/contrib/keras/python/keras/backend.py).

Instantiates an all-zeros variable of the same shape as another tensor.

#### Arguments:

    x: Keras variable or Keras tensor.
    dtype: String, dtype of returned Keras variable.
         None uses the dtype of x.
    name: String, name for the variable to create.


#### Returns:

    A Keras variable with the shape of x filled with zeros.

Example:
```python
    >>> from keras import backend as K
    >>> kvar = K.variable(np.random.random((2,3)))
    >>> kvar_zeros = K.zeros_like(kvar)
    >>> K.eval(kvar_zeros)
    array([[ 0.,  0.,  0.],
           [ 0.,  0.,  0.]], dtype=float32)
```