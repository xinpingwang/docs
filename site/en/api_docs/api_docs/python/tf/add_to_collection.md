

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.add_to_collection

``` python
add_to_collection(
    name,
    value
)
```



Defined in [`tensorflow/python/framework/ops.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.4/tensorflow/python/framework/ops.py).

See the guide: [Building Graphs > Graph collections](../../../api_guides/python/framework#Graph_collections)

Wrapper for `Graph.add_to_collection()` using the default graph.

See [`tf.Graph.add_to_collection`](../tf/Graph#add_to_collection)
for more details.

#### Args:

* <b>`name`</b>: The key for the collection. For example, the `GraphKeys` class
    contains many standard names for collections.
* <b>`value`</b>: The value to add to the collection.