Distributed Subgradient
=======================

.. literalinclude:: ../../../../examples/algorithms/distributed_subgradient/launcher.py
  :caption: examples/setups/distributed_subgradient/launcher.py

.. literalinclude:: ../../../../examples/algorithms/distributed_subgradient/results.py
  :caption: examples/setups/distributed_subgradient/results.py

The two files can be executed by issuing the following commands in the example folder:

.. code-block:: bash

  > mpirun -np 30 --oversubscribe python launcher.py
  > python results.py