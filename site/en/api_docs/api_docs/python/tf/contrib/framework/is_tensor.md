

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.contrib.framework.is_tensor

``` python
is_tensor(x)
```



Defined in [`tensorflow/python/framework/tensor_util.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.4/tensorflow/python/framework/tensor_util.py).

See the guide: [Framework (contrib)](../../../../../api_guides/python/contrib.framework)

Check whether `x` is of tensor type.

Check whether an object is a tensor. Equivalent to
`isinstance(x, [tf.Tensor, tf.SparseTensor, tf.Variable])`.

#### Args:

* <b>`x`</b>: An python object to check.


#### Returns:

`True` if `x` is a tensor, `False` if not.