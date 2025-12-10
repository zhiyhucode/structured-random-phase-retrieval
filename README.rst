Structured Random Phase Retrieval
===========================================================

Source code for the paper "`Structured Random Model for Fast and Robust Phase Retrieval <https://ieeexplore.ieee.org/document/10889235>`_" at ICASSP2025.

**Update:** A more complete study on the structured random model has been released. Please check out our new paper "`Structured Random Models for Phase Retrieval with Optical Diffusers <https://arxiv.org/abs/2510.14490>`_" with `code <https://github.com/zhiyhucode/structured-random-phase-retrieval-v2>`_!

Overview
--------

This work presents a novel structured random model for phase retrieval, reducing computational complexity from quadratic to log-linear compared to classical random models and maintaining robust reconstructions. The implementation is based on the open-source computational imaging library `deepinv <https://deepinv.github.io/deepinv/>`_.

Repository Structure
--------------------

- ``src/``: Contains source code for the structured random phase retrieval model
- ``experiment/``: Contains scripts to reproduce experiments and figures from the paper

Getting Started
---------------

1. Clone the repository:
   
   .. code-block:: bash

      git clone https://github.com/zhiyhucode/structured-random-phase-retrieval.git
      cd structured-random-phase-retrieval

2. Install the required dependencies:
   
   1. Install `uv <https://docs.astral.sh/uv/getting-started/installation/>`_;

   2. Run ``uv sync`` under the root directory of the project;

   3. Activate the environment using ``source .venv/bin/activate``;

3. Navigate to the experiment directory to run the scripts, e.g.:
   
   .. code-block:: bash

      cd experiment
      python struct_spec.py

4. Use the notebook ``experiment/visualization.ipynb`` to reproduce the figures from the paper.

Contributing
------------

We welcome contributions to improve the code or extend the research. Please submit a pull request or open an issue for any bugs or feature requests.

License
-------

This project is licensed under the BSD 3-Clause License - see the ``LICENSE`` file for details.

Citation
--------

If you find this work useful, please cite our paper:

.. code-block:: bibtex

   @inproceedings{hu2025structured,
     title={Structured Random Model for Fast and Robust Phase Retrieval},
     author={Hu, Zhiyuan and Tachella, Juli{\'a}n and Unser, Michael and Dong, Jonathan},
     booktitle={ICASSP 2025-2025 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
     pages={1--5},
     year={2025},
     organization={IEEE}
   }
