

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.keras.backend.dtype

``` python
dtype(x)
```



Defined in [`tensorflow/python/keras/_impl/keras/backend.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.4/tensorflow/python/keras/_impl/keras/backend.py).

Returns the dtype of a Keras tensor or variable, as a string.

#### Arguments:

* <b>`x`</b>: Tensor or variable.


#### Returns:

    String, dtype of `x`.

Examples:
```python
    >>> from keras import backend as K
    >>> K.dtype(K.placeholder(shape=(2,4,5)))
    'float32'
    >>> K.dtype(K.placeholder(shape=(2,4,5), dtype='float32'))
    'float32'
    >>> K.dtype(K.placeholder(shape=(2,4,5), dtype='float64'))
    'float64'
    # Keras variable
    >>> kvar = K.variable(np.array([[1, 2], [3, 4]]))
    >>> K.dtype(kvar)
    'float32_ref'
    >>> kvar = K.variable(np.array([[1, 2], [3, 4]]), dtype='float32')
    >>> K.dtype(kvar)
    'float32_ref'
```