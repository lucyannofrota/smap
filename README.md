# [Semantic Mapping] smap

Is a semantic mapping package built for ROS2 FOXY

## smap_core

## smap_classification_wrapper

The folder `src/classification_wrapper` contains the classification modules.

The `src/classification_wrapper.py` is a super class that wrapps the classifier in a ROS2 Node.

The folder `src/classification_wrapper/classifiers` contains the classifiers.

`src/classification_node.py` is responsible to launch each classifier node.


<depend>libpcl-all-dev</depend>