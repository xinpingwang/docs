

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.keras.backend.in_train_phase

``` python
in_train_phase(
    x,
    alt,
    training=None
)
```



Defined in [`tensorflow/python/keras/_impl/keras/backend.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.4/tensorflow/python/keras/_impl/keras/backend.py).

Selects `x` in train phase, and `alt` otherwise.

Note that `alt` should have the *same shape* as `x`.

#### Arguments:

* <b>`x`</b>: What to return in train phase
        (tensor or callable that returns a tensor).
* <b>`alt`</b>: What to return otherwise
        (tensor or callable that returns a tensor).
* <b>`training`</b>: Optional scalar tensor
        (or Python boolean, or Python integer)
        specifying the learning phase.


#### Returns:

Either `x` or `alt` based on the `training` flag.
the `training` flag defaults to `K.learning_phase()`.