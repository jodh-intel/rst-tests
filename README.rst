Title
=====

Link to `another file <another-file.rst>`_.

.. warning:: I am a warning!
   The warning can extend to multiple lines!

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
  
An example of the ``|today| substitution`` sphinx directive: |today|.

This is a sphinx reference to a section in another rST file: :ref:`my-reference-label`.

A sphinx reference to another file: :ref:`another-file` or :ref:`another-file.rst`.

An Include Example
------------------

The line below should *not* say "foo".

.. include:: include-me.rst

foo.

The End
-------

Thanks for reading!
