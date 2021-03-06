

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# Module: tf.compat

### Aliases:

* Module `tf.compat`
* Module `tf.contrib.meta_graph_transform.meta_graph_transform.compat`



Defined in [`tensorflow/python/util/compat.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.4/tensorflow/python/util/compat.py).

Functions for Python 2 vs. 3 compatibility.

## Conversion routines
In addition to the functions below, `as_str` converts an object to a `str`.


## Types
The compatibility module also provides the following types:

* `bytes_or_text_types`
* `complex_types`
* `integral_types`
* `real_types`

## Functions

[`as_bytes(...)`](../tf/compat/as_bytes): Converts either bytes or unicode to `bytes`, using utf-8 encoding for text.

[`as_str(...)`](../tf/compat/as_bytes): Converts either bytes or unicode to `bytes`, using utf-8 encoding for text.

[`as_str_any(...)`](../tf/compat/as_str_any): Converts to `str` as `str(value)`, but use `as_str` for `bytes`.

[`as_text(...)`](../tf/compat/as_text): Returns the given argument as a unicode string.

## Other Members

`bytes_or_text_types`

`complex_types`

`integral_types`

`real_types`

