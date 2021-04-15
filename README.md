MDD-on-LPN
====
Intro
----
It is the test and replication for some experiments proposed in the paper "Symbolic Verification of Current-state Opacity of Discrete Event Systems Using Petri Nets".
There are four object codes and executable programs: robot_mani.o, robot_mani, robot_mani_cyclic.o, robot_mani_cyclic, manu_sys_4_4.o, manu_sys_4_4, and  manu_sys_5_4.o, manu_sys_5_4. 

* "robot_mani.o and robot_mani" are the programs for the discret event system "robot manipulation" that is a parameterized labeled Petri net (this model can be obtained by https://mcc.lip6.fr/pdf/RobotManipulation-form.pdf). Readers should input a parameter k, where k=1, 2, ..., 10.

* "robot_mani_cyclic.o and robot_mani_cyclic" are the programs for the discret event system "robot manipulation", where there exist cyclic subnets of unobservable transitions. Readers should input a parameter k, where k=1, 2, ..., 10.

* "manu_sys_4_4.o and manu_sys_4_4" are the programs for the model of "parameterized manufacturing system", with the parameter beta=4 and eta=4.

* "manu_sys_5_4.o and manu_sys_5_4" are the programs for the model of "parameterized manufacturing system", with the parameter beta=5 and eta=4.

Package
-----
These executable programs are required to be run in Ubuntu 16.04 under the operating environment of "Meddly". 
This package could be obtained by "https://meddly.sourceforge.io/" with the licensed under the GNU Lesser General Public License Version 3.

Environment
-----
Readers are required to download the package of "Meddly" and configure the environment locally under the guidence of this package.

If readers need the source code for more details of our work or just for compiling, please contact me by "dongyifan199@gmail.com".
