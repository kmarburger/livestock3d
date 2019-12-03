# Livestock3D
Livestock Package for CPython

## Download and Install Livestock3D

* Download the Livestock Grasshopper zip [here](https://github.com/livestock3d/livestock3d/archive/master.zip)

* Create a folder at %appdata%\McNeel\Rhinoceros\5.0\scripts called livestock3d

* Put the files from the folder "grasshopper" in there.

* Create a folder called C:\livestock3d

* Put the files from the folder livestock3d there.

* Move the folder "Grasshopper Script" to a location of your choosing.

* Put the files from "UserObjects" into the Grasshopper UserObjects folder at %appdata%\Roaming\Grasshopper\UserObjects

* Create a conda environment by using the command prompt:

> conda create -n livestock_env python=3.6 numpy matplotlib

* Activate the environment using:

> conda activate livestock_env

* Extra conda packages can be installed here (ex "conda install numpy")

* To install the livestock Cpython dependencies using the following prompt (ignore any Cpython warnings):

> pip install livestock

More details about the Livestock project can be found [here](https://kongsgaard.eu/pages/LIVESTOCK.html)
