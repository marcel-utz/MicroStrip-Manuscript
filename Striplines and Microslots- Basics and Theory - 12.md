##  Striplines and Microslots: Basics and Theory
### Definition of a stripline
 The presence of conducting bodies imposes boundary conditions on the free propagation of electromagnetic waves. For an ideal conductor (an idealisation that certain metals, including Cu and Ag, approach quite closely), the electric field vector must stay perpendicular to the surface, while the magnetic field vector is required to stay parallel. 
Wave guides are long metallic structures of (usually) constant cross section. Electromagnetic waves of different types  (modes) can propagate in the longitudinal direction in such structures. They are classified as transverse electric (TE) or transverse magnetic (TM) waves. In TE waves, the electric field has no component in the longitudinal direction, while the longitudinal magnetic field vanishes for TM waves. Both TE and TM wave modes can only propagate if the wave length is smaller than the lateral dimensions of the wave guide. This leads to a minimum frequency (often referred to as the cutoff frequency) for propagating modes. Also, the relationship between the wavelength and the frequency for TE and TM modes is non-linear, leading to dispersion.
An additional type of propagating mode becomes possible if the walls of the wave guide are divided into several (at least 2) mutually insulated sections. In this case, an oscillatory voltage can be sustained between the separate conductors. Under these conditions, a propagating modes exist \textem{both} the electric and magnetic fields are transverse. Such TEM modes do not exhibit a cutoff frequency, and in general exhibit a linear relationship between wavelength and frequency. 
Frequencies of interest in magnetic resonance lie below 1.5 GHz. With usual dielectrics, this yields wave lengths of 20 cm or more. Therefore, TEM modes are commonly used in order to transport NMR signals, often in coaxial cables. This is different in electron paramagnetic resonance (EPR), where frequencies up to several hundred GHz occur. This requires the use of rectangular wave guides, in some cases with corrugated metalinterior surfaces.
Fig XXX shows some examples of common wave guide cross sections. Among these, the most familiar to NMR spectroscopists is that of the coaxial cable. Planar wave guide structures such as the microstrip (Fig XXXX b) and the stripline (Fig XXX c) are conveniently implemented on printed circuit boards, \cite{Barret:1955ie} and are very commonly used in the design of radio frequency and microwave circuits. 
### Characteristic Impedance and Transport Characteristics
For TEM modes, it is possible to attribute a current and a voltage amplitude to the travelling wave by integrating along the electric / magnetic field lines in the cross section. While the absolute voltage and current amplitudes depend on the level of wave excitation, their ratio (measured in Ohm) is a constant given purely by the cross section geometry, and the dielectric and magnetic properties of the insulating medium. This ratio is known as the characteristic impedance \m{Z_0} of the wave guide. Coaxial cables are commonly designed for a characteristic impedance of 50 Ohm.
### Theory of TEM Wave Modes
Maxwell’s curl equations couple the magnetic field \m{\mathbf{H}} and the electric field \m{\mathbf{E}}. If we assume a harmonic time evolution of the fields with angular frequency \m{\omega}, they become
\begin{eqnarray}
\nabla \times \mathbf{H} &= j \omega \epsilon \mathbf{E} \\
\nabla \times \mathbf{E} &= - j\omega \mu \mathbf{H}
\end{eqnarray}
where $j=\sqrt{-1}$ is the imaginary unit, and 
- assume time-harmonic evolution, and exponential propagation in the z direction with propagation constant gamma = alpha + i beta
- In the lossless case, alpha=0, fields are purely transverse and satisfy Laplace’ equation
- boundary conditions at the conductor require E perp Surf and H para surf
- 
- Characteristic impedance of a single stripline
- Steps in impedance
- Insertion of a microslot
### Transmission Line Resonators
- Dimensions and eigenfrequencies
- Q factor and sensitivity
- 
