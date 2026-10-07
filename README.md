# TVC-Finless-Rocket-PD-Simulator
A custom-built quaternion-based flight sim for a gimballed thrust finless rocket. Original purpose was to test the effect of induced roll on the rocket's trajectory. Gimballed motion controlled by PD structure.
This simulator was built off measurements for a future physical build as follows:

25.4 cm length, 350 grams weight, 5.08 cm diameter.

If you want to use it for your own rocket, be sure to change the file that you use for the motor profile. Also, be sure to do all the calculations for your own center mass, moment of inertia, torque, etc., based on your rocket's mass, length, and mass profiles.


THIS IS NOT INTENDED TO BE A ONE-SIZE-FITS-ALL SIM. It was built for a finless rocket with gimballed torque with the dimensions described above, and also with a mass curve that looks like this:

<img width="389" height="359" alt="image" src="https://github.com/user-attachments/assets/de7ee7dd-dbe2-400a-9f92-bd71b6e6ea5b" />

Of course, integrate only from 0 to 0.254. X axis is meters, y axis is kilos.
