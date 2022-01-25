# Nearest Neighbor Simulation V1.0
This is the python repository for geostatistical modeling with nearest neighbor simulation

In current state, we focus on the stochastic simulation with categorical variables

# Technical improvements:
Compared with other multiple-point statistics (MPS) programs, there are three main technical improvements within NNSIM:

(1) We introduce a prototype selection called fast condensed nearest neigbhor (FCNN) into MPS framework.
Compared with other pattern selection methods in MPS, our program finds representative patterns according to their influence on the simulation quality.

(2) A teacher-student architecture is proposed to augment pattern subset. With the aim of addressing missing data, the pattern subset is improved
with key patterns during the simulation.

(3) Our program organizes patterns with a ball tree.

# Applications:
There are three simulation applications in this repository:

(1) 2D benchmark channel simulation.

(2) 2D flume modeling with 4 geological categories and the grid segmentation.

(3) 3D sandstone modeling based on a 2D slice.

# Author:
Chen Zuo is a lecturer at the Chang'an University in China.

# Dependencies:
Scikit learn >= 0.23
Numpy >= 1.21.2
Scipy >= 1.7.1
Matplotlib >= 3.5.0

# Contact
Feel free to contact me at chenzuo789@outlook.com.
