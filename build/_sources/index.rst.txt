.. My First Book documentation master file, created by
   sphinx-quickstart on Fri Apr  1 14:56:21 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

=======================================================
Welcome to My First Book!
=======================================================
  .. epigraph::

  	Here I will share my musings on the complexity of the universe down to the mundane aspects of our everyday lives.  



.. raw:: latex

    \frontmatter
    \sphinxmaketitle

.. toctree::
    :hidden:
    :glob:

    preface

.. raw:: latex

    \sphinxtableofcontents

.. raw:: latex

    \mainmatter

.. toctree::
    :hidden:
    :includehidden:
    :numbered: 4
    :maxdepth: 4
    :caption: Contents
    :name: mastertoc
    :glob:

    1_the_enigma_of_schroeder

.. raw:: latex

    \backmatter

.. toctree::
    :hidden:
    :maxdepth: 1
    :caption: References
    :glob:

    R.Bibliography
