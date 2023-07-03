<h1>CAD & Simulation of a Standard Hollow Rectangular Waveguide</h1>


<h2>Description</h2>
This project analyzes and creates a standard air-filled copper WR-75 19.05mm x 9.525mm x 200mm rectangular waveguide for microwave applications. A theoretical TE10 wave (dominant mode) at 13.5GHz was used to obtain the cutoff frequency, wave impedance, phase constant, and attenuation constant due to the loss in the guide walls.
The goal of this project is to obtain the electromagnetic properties of the rectangular waveguide and to visualize the field distributions inside the guide as well as the surface current density on its walls.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Keysight EMPro 2023</b> 


<h2>Program walk-through:</h2>

<p align="center">
<b>Calculations of EM Properties:</b><br><br/>
  <img src="https://i.imgur.com/4WP67rN.png" height="80%" width="80%" alt="Calculations Table"/></p>
<br />
<br />
<br />
<p align="center">
<b>CAD of Rectangular Waveguide:</b><br><br/>
  <img src="https://i.imgur.com/rTETwHm.png" height="80%" width="80%" alt="RWG CAD"/></p><br>
  <p align="left">
  A CAD was created of the hollow copper WR-75 rectangular waveguide, and the ports of the waveguide were assigned to the z = 0mm and z = 200mm positions.</p>
<br />
<br />
<br />
<p align="center">
<b>Results of Finite Element Method Simulation:<br></b><br/>
  <img src="https://i.imgur.com/0PDEZef.png" height="80%" width="80%" alt="Electric Field Results"/></p>
  <p align="left">
  The plot of the electric field plot shows where the maximum and minimum amplitudes of the field are with respect to the rectangular waveguide, and shows how the wave will propagate through the guide.</p><br><br><br><br>
  <p align="center">
  <img src="https://i.imgur.com/3td20lB.png" height="80%" width="80%" alt="Surface Current Density Results"/></p>
  <p align="left">
  The plot of the surface current density on the walls of the copper conductor shows the magnitude and vector field of the current propagating through the conductor walls as the EM waves come in contact with the conductor.</p><br><br><br><br>
  <p align="center">
  <img src="https://i.imgur.com/6bO3dCk.png" height="80%" width="80%" alt="Propagation Constant Plot"/></p>
  <p align="left">
  A plot of the propagation constant was obtained to observe the cutoff frequency of the waveguide where the propagation constant goes to zero, as well as the value for the propagation constant for the wave at 13.5GHz. Numerical results were analyzed to determine the real and imaginary values of the propagation constant.</p><br><br><br><br>
  <p align="center">
  <img src="https://i.imgur.com/3KLz6zZ.png" height="80%" width="80%" alt="Wave Impedance Plot"/></p>
  <p align="left">
  A plot of the wave impedance was obtained to observe the cutoff frequency of the waveguide where the wave impedance spikes, as well as the value for the wave impedance for the wave at 13.5GHz. Numerical results were analyzed to determine the real and imaginary values of the wave impedance.</p><br><br>
<br />
<br />
<p align="center">
<b>Propagation Constant and Wave Impedance Simulation Results:</b><br><br/>
  <img src="https://i.imgur.com/kwV4pTm.png" height="80%" width="80%" alt="Results Table"/></p>
<br />
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
