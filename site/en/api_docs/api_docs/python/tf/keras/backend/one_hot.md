

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.keras.backend.one_hot

``` python
one_hot(
    indices,
    num_classes
)
```



Defined in [`tensorflow/python/keras/_impl/keras/backend.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.4/tensorflow/python/keras/_impl/keras/backend.py).

Computes the one-hot representation of an integer tensor.

#### Arguments:

* <b>`indices`</b>: nD integer tensor of shape
        `(batch_size, dim1, dim2, ... dim(n-1))`
* <b>`num_classes`</b>: Integer, number of classes to consider.


#### Returns:

(n + 1)D one hot representation of the input
with shape `(batch_size, dim1, dim2, ... dim(n-1), num_classes)`


#### Returns:

The one-hot tensor.