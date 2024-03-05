# TinyOS-TAG-Protocol
TinyOS Project developed for the course 'Processing and Analysis of Sensor Networks (INF511) with my lab partner at Technical University of Crete. 

My lab partner's name is Christos Ioannidis (https://github.com/kirisaki-momotaro) you can probably find the exact same project in his repositories too. 

=================================================================================================================================================================

Instructions for Running the Simulation

Step 1: Navigate to the TinyOS Folder
Change your directory to the TinyOS folder using the following command:

cd /home/tinyos/local/src/tinyos-2x/apps/tinyOS

Step 2: Build the Simulation
Execute the following command to build the simulation for MicaZ platform:

make micaz sim

Step 3: Create Topology File
Generate a topology file specifying the grid's width and height (D), as well as the range of each node (RANGE). Use the following Python command:

python ./topology_creator.py D RANGE

Step 4: Run the Simulation
Initiate the simulation by providing the total number of nodes (NUMBER_OF_NODES), which is also equal to D^2:

python ./mySimulation.py NUMBER_OF_NODES

These steps will ensure a smooth execution of the TinyOS simulation with your specified parameters.
