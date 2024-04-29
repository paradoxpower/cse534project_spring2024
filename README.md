This code is a Jupyter FABRIC Notebook designed to create a Topology that can
change the flow of a Node in the network based on the Network state.

A lot of the network set-up and configuration steps (up to section "Formulate Prometheus Queries") were pulled from a FABRIC tutorial for
MFLib/Promethues setup (https://github.com/fabric-testbed/jupyter-examples/blob/main/fabric_examples/mflib/mflib_example_index.ipynb)
and another tutorial for running DASH protocols in the FABRIC testbed (https://witestlab.poly.edu/blog/adaptive-video-reproducing/)

Those served as the foundation of the project. The specific topology and connection
between nodes was tailored to this experiment (within the "Establish the set of
Nodes" section of the notebook)

From section "Formulate Prometheus Queries" onward is where the project branches away
from example and becomes more original code. This is where the foundation and
setup provided by tutorials is leveraged to fulfill the goal of altering network
paths using the MFLib/Prometheus measurements.
