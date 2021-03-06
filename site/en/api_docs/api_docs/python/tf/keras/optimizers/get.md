

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.keras.optimizers.get

``` python
get(identifier)
```



Defined in [`tensorflow/python/keras/_impl/keras/optimizers.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.4/tensorflow/python/keras/_impl/keras/optimizers.py).

Retrieves a Keras Optimizer instance.

#### Arguments:

* <b>`identifier`</b>: Optimizer identifier, one of
        - String: name of an optimizer
        - Dictionary: configuration dictionary.
        - Keras Optimizer instance (it will be returned unchanged).
        - TensorFlow Optimizer instance
            (it will be wrapped as a Keras Optimizer).


#### Returns:

A Keras Optimizer instance.


#### Raises:

* <b>`ValueError`</b>: If `identifier` cannot be interpreted.