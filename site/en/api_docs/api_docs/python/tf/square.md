

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.square

``` python
square(
    x,
    name=None
)
```



Defined in [`tensorflow/python/ops/math_ops.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.4/tensorflow/python/ops/math_ops.py).

See the guide: [Math > Basic Math Functions](../../../api_guides/python/math_ops#Basic_Math_Functions)

Computes square of x element-wise.

I.e., \\(y = x * x = x^2\\).

#### Args:

* <b>`x`</b>: A `Tensor` or `SparseTensor`. Must be one of the following types: `half`,
    `float32`, `float64`, `int32`, `int64`, `complex64`, `complex128`.
* <b>`name`</b>: A name for the operation (optional).


#### Returns:

A `Tensor` or `SparseTensor`. Has the same type as `x`.