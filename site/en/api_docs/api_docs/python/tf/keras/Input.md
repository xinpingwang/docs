

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.keras.Input

### Aliases:

* `tf.keras.Input`
* `tf.keras.layers.Input`

``` python
Input(
    shape=None,
    batch_size=None,
    name=None,
    dtype=None,
    sparse=False,
    tensor=None,
    **kwargs
)
```



Defined in [`tensorflow/python/keras/_impl/keras/engine/topology.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.4/tensorflow/python/keras/_impl/keras/engine/topology.py).

`Input()` is used to instantiate a Keras tensor.

A Keras tensor is a tensor object from the underlying backend
(Theano or TensorFlow), which we augment with certain
attributes that allow us to build a Keras model
just by knowing the inputs and outputs of the model.

For instance, if a, b and c are Keras tensors,
it becomes possible to do:
`model = Model(input=[a, b], output=c)`

The added Keras attribute is:
    `_keras_history`: Last layer applied to the tensor.
        the entire layer graph is retrievable from that layer,
        recursively.

#### Arguments:

* <b>`shape`</b>: A shape tuple (integers), not including the batch size.
        For instance, `shape=(32,)` indicates that the expected input
        will be batches of 32-dimensional vectors.
* <b>`batch_size`</b>: optional static batch size (integer).
* <b>`name`</b>: An optional name string for the layer.
        Should be unique in a model (do not reuse the same name twice).
        It will be autogenerated if it isn't provided.
* <b>`dtype`</b>: The data type expected by the input, as a string
        (`float32`, `float64`, `int32`...)
* <b>`sparse`</b>: A boolean specifying whether the placeholder
        to be created is sparse.
* <b>`tensor`</b>: Optional existing tensor to wrap into the `Input` layer.
        If set, the layer will not create a placeholder tensor.
* <b>`**kwargs`</b>: deprecated arguments support.


#### Returns:

    A tensor.

Example:

    ```python
    # this is a logistic regression in Keras
    x = Input(shape=(32,))
    y = Dense(16, activation='softmax')(x)
    model = Model(x, y)
    ```


#### Raises:

* <b>`ValueError`</b>: in case of invalid arguments.