MDD-on-LPN
====
Intro
----
There are four executable programs: robot_mani, robot_mani_cyclic, manu_sys_4_4, and  manu_sys_5_4.

* "robot_mani" is the program for the discret event system "robot manipulation", which is a parameterized labeled Petri net (this model can be obtained by https://mcc.lip6.fr/pdf/RobotManipulation-form.pdf). Readers should input a parameter k, where k=1, 2, ..., 10.

`robot manipulation 5`

* "robot_mani_cyclic" is the program for the discret event system "robot manipulation", where there exist cyclic subnets of unobservable transitions. Readers should input a parameter k, where k=1, 2, ..., 10.

* "manu_sys_4_4" is the program for the model of "parameterized manufacturing system", with the parameter beta=4 and eta=4.

* "manu_sys_5_4" is the program for the model of "parameterized manufacturing system", with the parameter beta=5 and eta=4.

Package
-----
These executable programs are required to be run in Linux under the operating environment of "Meddly". 
This package could be obtained by "https://meddly.sourceforge.io/" with the licensed under the GNU Lesser General Public License Version 3.

Environment
-----
Readers are required to download the package of "Meddly" and configure the environment locally under the guidence of this package.
