

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.keras.layers.concatenate

``` python
concatenate(
    inputs,
    axis=-1,
    **kwargs
)
```



Defined in [`tensorflow/python/keras/_impl/keras/layers/merge.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.4/tensorflow/python/keras/_impl/keras/layers/merge.py).

Functional interface to the `Concatenate` layer.

#### Arguments:

* <b>`inputs`</b>: A list of input tensors (at least 2).
* <b>`axis`</b>: Concatenation axis.
* <b>`**kwargs`</b>: Standard layer keyword arguments.


#### Returns:

A tensor, the concatenation of the inputs alongside axis `axis`.