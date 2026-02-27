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
This damping increases the amount of energy lost per cycle.

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

The QCM measurement is achieved by monitoring the change in resonance frequency, Δf, when mass is added to, or removed from, the sensor surface. When mass is added, the resonance frequency decreases, Figure 3, and vice versa.

<div align="center">
<img width="3251" height="1329" alt="image" src="https://github.com/user-attachments/assets/70007173-3c08-433b-9cfb-34e24da57506" />

Figure 3. QCM technology collects time-resolved information on frequency changes of the QCM sensor and can detect mass uptake at the sensor surface. The schematic illustration shows (I) a bare sensor surface and a stable baseline of Δf. In step (II), molecules adsorb to the sensor surface which results in a frequency decrease. In (III), the surface uptake has been completed and the frequency response has stabilized. The frequency shift between I and III can be used to quantify the mass uptake at the sensor surface.
</div>

By following the changes in Δf, molecule – surface interaction can be detected and mass uptake and release from the surface can be quantified, Figure 4.

<div align="center">
<img width="2367" height="999" alt="image" src="https://github.com/user-attachments/assets/636bb929-ccb8-4325-b11d-1e98c90cd982" />

Figure 3. Schematic illustration of molecules (left) adsorbing to and (right) desorbing from the QCM sensor surface. The bottom panels illustrate the resulting changes in quantified mass, i.e., mass uptake as molecules adsorb and mass loss as they leave the surface.
</div>

## 4. Equivalent Circuit Model

The quartz crystal oscillations can be modeled in a similar fashion to a mechanical
spring-mass-damper simple harmonic oscillator or an electrical RLC circuit. In the case
of an RLC circuit (Figure 4a), R represents the energy dissipated during the oscillation,
C represents the energy stored and L represents the inertial component related to the
displaced mass. Therefore, the impedance spectrum of the quartz crystal can be used
to extract the values of R, L and C. An example Impedance spectrum for a RLC circuit
is shown in Figure 4b. Here, a sharp spike is observed at the resonate frequency (f0)
and therefore a change in mass results in a change in frequency .

<div align="center">
<img width="1066" height="311" alt="image" src="https://github.com/user-attachments/assets/343a37c6-0821-4c4d-ad69-90e85ab62702" />

Figure 4. (a) Scheme of an RLC Circuit for modeling the Impedance response of a quartz
crystal (b) Impedance spectrum for a series RCL circuit
</div>

In practice, the act of adding electrical contacts to the crystal (represented as
gold contacts in Figure 1 and 2) adds an additional capacitance. This capacitance is added
into the RCL model and is denoted the Butterworth-Van Dyke (BVD) Model (Figure 5a).
This circuit model results in two resonant frequencies fs and fp ,(Figure 5b) which
represent the series resonant frequency (same as the original RLC circuit in Figure 4a)
and parallel resonant frequency. In the example of the Stanford Research Systems
(SRS) QCM, the parallel capacitance is manually canceled out on the front of the
instrument and the series resonant frequency is measured.

<div align="center">
<img width="1055" height="323" alt="image" src="https://github.com/user-attachments/assets/dbb0f041-f05d-49b9-b70f-b26b636e6176" />

Figure 5. (a) Equivalent circuit for the Butterworth-Van Dyke Model (b) Impedance spectrum
for the BVD model
</div>

As previously mentioned, the resonant frequency is dependent on the inductor
element, which itself is a function of the mass displacement, therefore, the mass
change of the quartz crystal can be correlated with a change in the resonant frequency.
This dependance is represented as the Sauerbry equation (Equation 1) and can be
further simplified to Equation 2 where Cf is the calibration constant. This constant is
usually 56.6 Hz cm2 μg-1 for a 5 MHz At-cut quartz crystal in air, however it is
recommended to calibrate each crystal individually. Additionally this analysis assumes
a thin rigid film and the decrease in frequency is small in comparison to the resonance
frequency (5 MHz)

<img width="1046" height="284" alt="image" src="https://github.com/user-attachments/assets/64fdc9b1-0dd8-426a-b996-a1d9b6345ab4" />

## References

https://www.biolinscientific.com/blog/what-is-qcm

https://www.gamry.com/application-notes/qcm/basics-of-a-quartz-crystal-microbalance/

https://en.wikipedia.org/wiki/Quartz_crystal_microbalance
