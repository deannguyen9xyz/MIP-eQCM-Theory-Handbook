# eQCM Principle

## 1. What is QCM
A quartz crystal microbalance (QCM), also known as quartz microbalance (QMB) and sometimes referred to as a quartz crystal nanobalance (QCN), 
measures mass variation per unit area by monitoring the change in resonance frequency of a quartz crystal resonator.

## 2. Quartz and Piezoelectric Effect
Quartz is one member of a family of crystals that exhibit the piezoelectric effect. Quartz is by far the most widely utilized material for 
the development of instruments containing oscillators partly due to historical reasons (the first crystals were harvested naturally) and partly due to its commercial availability (synthetically grown nowadays).

Piezoelectricity refers to the electric charge 
that accumulates in certain solid materials—such as crystals, ceramics, and some biological materials (e.g., bone, DNA, 
and proteins)—in response to applied mechanical stress. Conversely, the application of a potential to the same material results in 
a mechanical strain (a deformation). Removal of the potential allows the crystal to restore to its original orientation.
Quartz has a vibrational mode of thickness shear deformation as shown below in Figure 1.

<div align="center">
<img width="170" height="77" alt="image" src="https://github.com/user-attachments/assets/316767f3-0347-4faf-b3e3-e9068d09ed9b" />

Quartz Crystal No Applied Potential

<img width="170" height="77" alt="image" src="https://github.com/user-attachments/assets/cf73587c-c9b8-48ae-b1fd-3979bd6f2907" />

Quartz Crystal Under Applied Potential

**Figure 1**. Graphical Representation of Thickness Shear Deformation.</div>

The application of an alternating potential (a sine wave in nearly all cases) to the crystal faces causes the crystal to oscillate. 
When the thickness of the crystal (tq) is twice the acoustical wavelength, a standing wave can be established where the inverse of 
the frequency of the applied potential is of the period of the standing wave. This frequency is called the resonant frequency, f0, and is given by the equation

<img width="110" height="59" alt="image" src="https://github.com/user-attachments/assets/822c0d99-164f-4514-aba5-ecd7f9eec776" />

where μq is the shear modulus (a ratio of sheer stress to shear strain), ρq is the density, and tq is the crystal thickness. 
The amount of energy lost during oscillation at this frequency is at a minimum. 
The ratio of peak energy stored to energy lost per cycle is referred to as the quality factor, Q, and is given by the equation

<img width="95" height="52" alt="image" src="https://github.com/user-attachments/assets/4d76c09e-97a6-4955-8f17-f155c26236c7" />

where fc is the center frequency and fFWHM is the full width at half max. This full width at half max is also called the bandwidth. 
For quartz crystals in air, Q can exceed 100,000 while in solution Q decreases to ~3000. This is because the crystal has been damped by the solution. 
This damping increases the amount of energy lost per cycle, decreasing Q as shown in Figure 2 below.

<img width="268" height="198" alt="image" src="https://github.com/user-attachments/assets/4999fc83-ed7f-4020-a891-8fb14cb8342b" />

Figure 2. Comparison of High Q (solid line) and Low Q (dashed line).

## 3.QCM working principle
The core of QCM technology is the sensor, where a thin disk of the piezoelectric material is sandwiched between two electrodes.
In Figure 2A, when applying an electric field over the disk, there will be a mechanical oscillation. In Figure 2B,
the resonance frequency depends on the sensor design and is typically 5-10MHz, but it can be both lower and higher.

<div align="center">
<img width="2739" height="834" alt="image" src="https://github.com/user-attachments/assets/05202327-db64-4a2d-9bd9-bd59a742421a" />

**Figure 2**. Schematic illustration of a (A) QCM sensor made of a thin disk of a piezoelectric material sandwiched between two electrodes. 
The disk material is typically quartz, and the electrodes are typically made of gold, but other materials can be used. 
In (B), an alternating voltage is applied over the sensor, inducing a mechanical oscillation of the sensor
</div>

## References

https://www.biolinscientific.com/blog/what-is-qcm

https://www.gamry.com/application-notes/qcm/basics-of-a-quartz-crystal-microbalance/

https://en.wikipedia.org/wiki/Quartz_crystal_microbalance
