

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.keras.backend.switch

``` python
switch(
    condition,
    then_expression,
    else_expression
)
```



Defined in [`tensorflow/python/keras/_impl/keras/backend.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.4/tensorflow/python/keras/_impl/keras/backend.py).

Switches between two operations depending on a scalar value.

Note that both `then_expression` and `else_expression`
should be symbolic tensors of the *same shape*.

#### Arguments:

* <b>`condition`</b>: scalar tensor (`int` or `bool`).
* <b>`then_expression`</b>: either a tensor, or a callable that returns a tensor.
* <b>`else_expression`</b>: either a tensor, or a callable that returns a tensor.


#### Returns:

The selected tensor.