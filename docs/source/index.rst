.. BEND documentation master file, created by
   sphinx-quickstart on Sat Aug 26 12:57:26 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to 🧬 BEND's documentation!
===================================

`BEND <https://github.com/frederikkemarin/BEND/>`_ is a **Ben**\ chmark collection for evaluating the performance of **D**\ NA language models (LMs).
The BEND codebase serves three purposes:

* Providing a **unified interface for computing embeddings** from pretrained DNA LMs.

* **Extracting sequences from reference genomes using coordinates** listed in bed files, and computing embeddings for these sequences for training and evaluating models.

* **Training lightweight supervised CNN models** that use **DNA LM embeddings** as input, and evaluating their performance on a variety of tasks.


The documentation covers the BEND codebase and includes instructions on how to extend it to new LMs and tasks. For a tutorial on how to run BEND on existing tasks, please refer to the 
`README file <https://github.com/frederikkemarin/BEND>`_ on GitHub.


.. toctree::
   :maxdepth: 2
   :caption: Contents:

   hydra
   bend.utils.embedders
   adding_embedders
   bend.models
   bend.utils
   bend.io


.. automodule:: bend.models
    :members:

.. automodule:: bend.utils
    :members:
    :no-index: embedders

.. automodule:: bend.io
    :members:


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
