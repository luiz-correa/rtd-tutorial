Uso
=====

.. _installation:

Instalação
------------

.. code-block:: Configuração > Escalas de plantão ``Plantão Médico``

To use Lumache, first install it using pip-----:

.. code-block:: Configuração > Escala

   (.venv) $ pip install lumache...

Criando receitas
----------------

Lista de ingredients,
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

