Title
=====

foo bar.

The text below is rendered in a fixed font using the standard rST ``::`` syntax::

  $ echo foo

An example of the ``highlight`` sphinx directive (**XXX: doesn't render in github!**):
  
.. highlight:: c

  func()

An example of the ``code-block`` sphinx directive:

.. code-block:: c

  int i;
  i = 17;
  
  The end.

An example of the ``|today| substitution`` sphinx directive: |today|.

This is a sphinx reference to a section in another rST file: :ref:`my-reference-label`.

A sphinx reference to another file: :ref:`another-file`.
