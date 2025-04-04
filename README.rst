Structured Random Model for Fast and Robust Phase Retrieval
===========================================================

This repository contains the source code for the paper submission "Structured Random Model for Fast and Robust Phase Retrieval" to ICASSP2025.

Overview
--------

Our work presents a novel model for phase retrieval, offering both speed and robustness. The implementation is based on the open-source computational imaging library `deepinv <https://github.com/deepinv/deepinv>`_.

Repository Structure
--------------------

- ``experimental/paper/scripts/``: Contains scripts for data generation
- ``experimental/paper/notebooks/``: Includes Jupyter notebooks for figure generation

Getting Started
---------------

1. Clone the repository:
   
   .. code-block:: bash

      git clone https://github.com/zhiyhucode/structured-random-phase-retrieval.git
      cd structured-random-phase-retrieval

2. Install the required dependencies:
   
   1. Install `uv <https://docs.astral.sh/uv/getting-started/installation/>`;
   1. Run ``uv sync`` under the root directory of the project;
   1. Optionally, run ``uv pip install --no-build-isolation fast-hadamard-transform``, if you have a GPU;
   1. Activate the environment using ``source .venv/bin/activate``;

3. Navigate to the scripts directory to generate data, e.g.:
   
   .. code-block:: bash

      cd experimental/paper/scripts
      python pseudorandom_spectral.py

4. Use the notebooks in ``experimental/paper/notebooks/`` to reproduce the figures from the paper.

Contributing
------------

We welcome contributions to improve the code or extend the research. Please submit a pull request or open an issue for any bugs or feature requests.

License
-------

This project is licensed under the BSD 3-Clause License - see the ``LICENSE`` file for details.

Citation
--------

If you are interested in citing the work, please cite our paper:

.. code-block:: bibtex

   @misc{hu2024structuredrandommodelfast,
      title={Structured Random Model for Fast and Robust Phase Retrieval}, 
      author={Zhiyuan Hu and Julián Tachella and Michael Unser and Jonathan Dong},
      year={2024},
      eprint={2409.05734},
      archivePrefix={arXiv},
      primaryClass={physics.optics},
      url={https://arxiv.org/abs/2409.05734}, 
    }
