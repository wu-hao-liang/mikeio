# Generic


MIKE IO has generic dfs functionality that works for all dfs files: 

* `concat()` - Concatenates files along the time axis
* `extract()` - Extract timesteps and/or items to a new dfs file
* `diff()`  - Calculate difference between two dfs files
* `sum()`  - Calculate the sum of two dfs files
* `scale()`  - Apply scaling to any dfs file
* `avg_time()`  - Create a temporally averaged dfs file
* `quantile()` - Create a dfs file with temporal quantiles

All methods in the generic module creates a new dfs file.

```python
>>> from mikeio import generic
>>> generic.concat(["fileA.dfs2", "fileB.dfs2"], "new_file.dfs2")
```

See the [Generic notebook](https://nbviewer.jupyter.org/github/DHI/mikeio/blob/main/notebooks/Generic.ipynb) for more examples.


## Generic API

```{eval-rst}
.. automodule:: mikeio
	:members:

.. automodule:: mikeio.generic
	:members:
```