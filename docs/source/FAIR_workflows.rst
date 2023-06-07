FAIR Workflows
=====

.. _FAIR Workflows:

FAIR Workflows
------------

Downstream of the FAIR Data Cube, we envision the use of FAIR workflows in the federated analyses.
We define FAIR workflows as computational workflows that follow the FAIR4RS principles (add ref). Also, practical redommendations on the development of FAIR worklows are previously decribed by experienced workflow developers within the X-omics initiative (add ref).

Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

