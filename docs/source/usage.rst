=====
Usage
=====

.. _usage:
--
UI
--
----
PyPI
----

Completeness
------------

Calculate the completeness metric for each column and the overall completeness metric for the dataset.

Application
...........

.. code-block:: python

   import aidrin

   # Calculate completeness
   completeness_result = aidrin.completeness(file=df)

   # Print the result
   print(completeness_result)

Parameters
..........

**file** : DataFrame
   The input pandas DataFrame for which completeness metrics need to be calculated.

Returns
.......

A dictionary containing completeness scores for each column and the overall completeness score.

Examples
........

.. code-block:: python

   {
      'Completeness scores': {'A': 0.75, 'B': 0.75, 'C': 1.0, 'D': 0.0},
      'Overall Completeness': 0.62
   }

Notes
.....

- The function computes the proportion of non-missing values in each column and then averages these proportions to get an overall completeness score.
- It provides a bar chart visualization of completeness scores for each column.
- In case of any errors, the function returns an error message in the output dictionary.


.. autosummary::
   :toctree: generated


