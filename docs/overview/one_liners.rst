One liners
----------

.. grid:: 1 1 3 3
    :gutter: 4

    .. grid-item-card:: ``ivy.compile()``
        :link: one_liners/compile.rst

        Compiles a ``Callable`` or set of them into an Ivy graph.

    .. grid-item-card:: ``ivy.transpile()``
        :link: one_liners/transpile.rst

        Transpiles a ``Callable`` or set of them from a ``source`` framework to another
        framework.

    .. grid-item-card:: ``ivy.unify()``
        :link: one_liners/transpile.rst

        Transpiles an object into Ivy code. It's an alias to
        ``ivy.transpile(..., to="ivy", ...)``

.. toctree::
    :hidden:
    :maxdepth: -1

    one_liners/compile.rst
    one_liners/transpile.rst
