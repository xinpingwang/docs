

page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# tf.contrib.metrics.streaming_false_negatives

``` python
streaming_false_negatives(
    predictions,
    labels,
    weights=None,
    metrics_collections=None,
    updates_collections=None,
    name=None
)
```



Defined in [`tensorflow/contrib/metrics/python/ops/metric_ops.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.4/tensorflow/contrib/metrics/python/ops/metric_ops.py).

See the guide: [Metrics (contrib) > Metric `Ops`](../../../../../api_guides/python/contrib.metrics#Metric_Ops_)

Computes the total number of false negatives.

If `weights` is `None`, weights default to 1. Use weights of 0 to mask values.

#### Args:

* <b>`predictions`</b>: The predicted values, a `Tensor` of arbitrary dimensions. Will
    be cast to `bool`.
* <b>`labels`</b>: The ground truth values, a `Tensor` whose dimensions must match
    `predictions`. Will be cast to `bool`.
* <b>`weights`</b>: Optional `Tensor` whose rank is either 0, or the same rank as
    `labels`, and must be broadcastable to `labels` (i.e., all dimensions
    must be either `1`, or the same as the corresponding `labels`
    dimension).
* <b>`metrics_collections`</b>: An optional list of collections that the metric
    value variable should be added to.
* <b>`updates_collections`</b>: An optional list of collections that the metric update
    ops should be added to.
* <b>`name`</b>: An optional variable_scope name.


#### Returns:

* <b>`value_tensor`</b>: A `Tensor` representing the current value of the metric.
* <b>`update_op`</b>: An operation that accumulates the error from a batch of data.


#### Raises:

* <b>`ValueError`</b>: If `weights` is not `None` and its shape doesn't match `values`,
    or if either `metrics_collections` or `updates_collections` are not a list
    or tuple.