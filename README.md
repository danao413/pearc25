# pearc25
Compilation files, modules loaded, and scripts to run calculations from "A Benchmark of the Density Functional Theory Code FHI-aims on the A64FX and GRACE Processors on the Ookami Testbed"

To run FHI-aims on these systems, we used the atomic simulation environment (ASE), an open-source python package.
First, load the modules that match the compilation used (ie loading the Intel modules for an Intel compilation).
Next, download the benzene file from https://www.ccdc.cam.ac.uk/structures/Search?Ccdcid=benzeN&DatabaseToSearch=Published.
Make a supercell of benzene (or just use the benzene cif file without a supercell).
Then, edit the species defaults and ASE run command in the "run_aims.py" file.
Finally, run "python run_aims.py".

