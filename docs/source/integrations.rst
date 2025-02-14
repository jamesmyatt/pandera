.. _integrations:

Integrations
============

Pandera ships with integrations with other tools in the Python ecosystem, with
the goal of interoperating with libraries that you know and love.


.. list-table::
   :widths: 25 75

   * - :ref:`Hypothesis <data synthesis strategies>`
     - Use the hypothesis library to generate valid data under your schema's constraints.
   * - :ref:`Pydantic <pydantic_integration>`
     - Use pandera SchemaModels when defining  your pydantic BaseModels
   * - :ref:`Mypy <mypy_integration>`
     - Type-lint your pandas and pandera code with mypy for static type safety [experimental 🧪]

.. toctree::
    :maxdepth: 1
    :caption: Introduction
    :hidden:

    Pydantic <pydantic_integration>
    Mypy <mypy_integration>


.. note::

   Don't see a library that you want supported? Check out the
   `github issues <https://github.com/pandera-dev/pandera/issues>`__ to see if
   that library is in the roadmap. If it isn't, open up a
   `new issue <https://github.com/pandera-dev/pandera/issues/new?assignees=&labels=enhancement&template=feature_request.md&title=>`__
   to add support for it!
