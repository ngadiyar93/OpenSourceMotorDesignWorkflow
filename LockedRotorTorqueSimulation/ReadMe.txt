Simulates Locked Rotor Torque for different current values

Run: LockedRotorTorqueSimulation.py to set up the problem and run the simulation

Individual Torque Plots and Data are stored in Plots and ExcelResults folder, respectively.

This simulation is setup as multiprocessing. i.e., Multiple instances of FEMM (Different Current Instances) are run in parallel to reduce simulation time.

Achieved 4x Simulation time reduction by multiprocessing