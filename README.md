# Multiple Degrees-Of-Freedom Input Devices for Interactive Command and Control within Virtual Reality in Industrial Visualisations
Adding multiple DOF input devices with suitable guidelines does not necessarily imply natural and intuitive behaviours. For example, it is still difficult to navigate (or use) VR applications and do other tasks simultaneously as not all input devices and VR applications can work together. Heterogeneous driver controls are not all compatible and usable with different VR and visualisation applications. This means some users stop using applications as they can not use their favourite controller. LISU is a layered framework specifically designed for managing multiple, incompatible input device controllers and is perfect for evaluating different systems.   

LISU's multilayered architecture allows interaction directly with the rendered volume and seamlessly uses multiple different input devices to operate the same visualisation API parameters. LISU unifies the roles of multiple APIs for input management to resolve interoperability and compatibility issues caused by the heterogeneity of input controllers, thus enabling a large number of multiple DOF to create a natural and intuitive behaviour.  

Tu run LISU, we recommend using Anaconda. Anaconda is a distribution of packages built for data science. It comes with conda, a package, and environment manager. We usually use conda to create environments for isolating our projects that use different versions of Python and/or different version of packages.

1.	Download the Anaconda installer
2.	Double click the installer to launch. Complete all the steps for the installation of Anaconda (see: https://docs.anaconda.com/anaconda/install/windows/)
3.	Install Python. V.3.7. If you have a Python 3 environment with Anaconda installed, you can now easily update it to Python 3.7: conda install python=3.7 anaconda=custom
4.	Create a new environment: conda create -n yourenvname python=3.7 anaconda
5.	Install PyGame: pip pygame install
6.	Install PyUSB: pip install pyusb
7.	Install RDFLib: pip install rdflib
8.  Download the folder "demo"
9.  Open folder "dist"
9.	Execute the command pylisu.exe
10.	 From the menu you can select from 3 options: 1) start with the automatic setup for the input devices, 2) see the supported devices in the ontology, or q) exit the program.

UDP port 7755 outgoing from clients that will interface with VR applications.

Ref: Sandoval, Mario (2021), “Multiple Degrees-Of-Freedom Input Devices for Interactive Command and Control within Virtual Reality in Industrial Visualisations”, Mendeley Data, V1, doi: 10.17632/yhnfc4cpmt.1
