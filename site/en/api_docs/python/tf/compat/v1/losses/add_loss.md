page_type: reference
<style>{% include "site-assets/css/style.css" %}</style>

<!-- DO NOT EDIT! Automatically generated file. -->

# tf.compat.v1.losses.add_loss


<table class="tfo-notebook-buttons tfo-api" align="left">

<td>
  <a target="_blank" href="https://github.com/tensorflow/tensorflow/tree/r2.0/tensorflow/python/ops/losses/util.py#L182-L194">
    <img src="https://www.tensorflow.org/images/GitHub-Mark-32px.png" />
    View source on GitHub
  </a>
</td></table>



Adds a externally defined loss to the collection of losses.

``` python
tf.compat.v1.losses.add_loss(
    loss,
    loss_collection=tf.GraphKeys.LOSSES
)
```



<!-- Placeholder for "Used in" -->


#### Args:


* <b>`loss`</b>: A loss `Tensor`.
* <b>`loss_collection`</b>: Optional collection to add the loss to.