*********************************
Welcome to Tombo's documentation!
*********************************

Tombo is a suite of tools primarily for the identification of modified nucleotides from nanopore sequencing data.

Tombo also provides tools for the analysis and visualization of raw nanopore signal.

------------
Installation
------------

Basic Tombo installation (python2.7 support only)::

    # install via bioconda environment
    conda install -c bioconda ont-tombo

    # or install pip package (numpy install required before tombo for cython optimization)
    pip install numpy
    pip install ont-tombo

See :doc:`examples` for common workflows.

------
Naming
------

Tombo Ahi is a Japanese name for albacore (which is also the Oxford Nanopore Technologies basecaller). So use albacore to identify canonical bases and then use Tombo to detect more exotic, non-canonical bases.

--------
Contents
--------

.. toctree::
   :maxdepth: 2

   examples
   resquiggle
   modified_base_detection
   text_output
   plotting
   filtering
   model_training

-------------------------
Full API reference (beta)
-------------------------

.. toctree::
   :maxdepth: 2

   tombo

-------------------
Documentation Index
-------------------

* :ref:`genindex`
* :ref:`modindex`
