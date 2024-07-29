1. Current is a vector quantity https://youtu.be/g7DKec-IzoQ?feature=shared
Sure, here’s an extensive list of formulas for network theory in electricity, ranging from basic concepts to advanced topics:

### Basic Concepts


1. Electric Charge:
   - Q = ne (where n is the number of electrons, e is the elementary charge)

2. Law of Conservation of Charge:
   - Total charge before a process = Total charge after the process

3. Electric Current:
   - I = dQ/dt (where Q is the charge, t is time)

4. Conventional Current vs. Electron Current:
   - Conventional current flows from positive to negative, whereas electron flow is from negative to positive.

5. Electric Potential Difference (Voltage):
   - V = W/Q (where W is work done, Q is charge)

6. Electric Power:
   - P = VI
   - P = I^2R
   - P = V^2/R

Circuit Elements

1. Resistor:
   - V = IR

2. Ohm’s Law:
   - V = IR
   - I = V/R
   - R = V/I

3. Inductor:
   - V_L = L dI/dt
   - Energy Stored: E = 1/2 L I^2

4. Capacitor:
   - Q = CV
   - I = C dV/dt
   - Energy Stored: E = 1/2 CV^2

Series and Parallel Combinations

1. Series Resistors:
   - R_total = R1 + R2 + ... + Rn

2. Parallel Resistors:
   - 1/R_total = 1/R1 + 1/R2 + ... + 1/Rn

3. Series Capacitors:
   - 1/C_total = 1/C1 + 1/C2 + ... + 1/Cn

4. Parallel Capacitors:
   - C_total = C1 + C2 + ... + Cn

5. Series Inductors:
   - L_total = L1 + L2 + ... + Ln

6. Parallel Inductors:
   - 1/L_total = 1/L1 + 1/L2 + ... + 1/Ln

Kirchhoff’s Laws

1. Kirchhoff’s Current Law (KCL):
   - sum I_in = sum I_out

2. Kirchhoff’s Voltage Law (KVL):
   - sum V = 0 (around a closed loop)

AC Circuits

1. Impedance:
   - Resistor: Z_R = R
   - Inductor: Z_L = jωL
   - Capacitor: Z_C = 1/jωC

2. Reactance:
   - Inductive Reactance: X_L = ωL
   - Capacitive Reactance: X_C = 1/ωC

3. Phasor Relationships:
   - V_R = IR
   - V_L = I(jωL)
   - V_C = I (1/jωC)

4. Power in AC Circuits:
   - Apparent Power: S = VI*
   - Real Power: P = VI cos(θ)
   - Reactive Power: Q = VI sin(θ)
   - Power Factor: pf = cos(θ)

Network Theorems

1. Superposition Theorem:
   - Total response in any element is the sum of the responses caused by each independent source acting alone.

2. Thevenin’s Theorem:
   - Any network can be replaced by an equivalent voltage source V_th in series with a resistance R_th.

3. Norton’s Theorem:
   - Any network can be replaced by an equivalent current source I_N in parallel with a resistance R_N.

4. Maximum Power Transfer Theorem:
   - Maximum power is delivered to the load when R_L = R_th.

Advanced Topics

1. Laplace Transform:
   - V(s) = L{v(t)}
   - I(s) = L{i(t)}
   - Impedance in s-domain:
     - Resistor: Z_R(s) = R
     - Inductor: Z_L(s) = sL
     - Capacitor: Z_C(s) = 1/sC

2. Transfer Functions:
   - H(s) = V_out(s)/V_in(s)

3. State-Space Analysis:
   - State Equations: dot{x}(t) = Ax(t) + Bu(t)
   - Output Equation: y(t) = Cx(t) + Du(t)

4. Fourier Series and Fourier Transform:
   - Fourier Series: f(t) = sum C_n e^(j n ω0 t)
   - Fourier Transform: F(ω) = ∫ f(t) e^(-j ω t) dt

5. Bode Plot:
   - Magnitude Plot: 20 log10|H(jω)|
   - Phase Plot: angle H(jω)

6. Nyquist Plot:
   - Plot of H(jω) on the complex plane as ω varies from -∞ to ∞.

7. Root Locus:
   - Graphical representation of the roots of the characteristic equation of a control system as a system parameter is varied.

Network Analysis Techniques

1. Mesh Analysis:
   - Use KVL to write equations for each mesh (independent loop).
   - Solve the resulting system of linear equations to find mesh currents.

2. Nodal Analysis:
   - Use KCL to write equations for each node (excluding reference node).
   - Solve the resulting system of linear equations to find node voltages.

Specialized Components and Circuits

1. RLC Circuits:
   - Series RLC Circuit: Z = R + j(ωL - 1/ωC)
   - Parallel RLC Circuit: Y = G + j(ωC - 1/ωL)

2. Transformers:
   - Turns Ratio: N1/N2 = V1/V2 = I2/I1
   - Impedance Reflection: Z_in = (N1/N2)^2 Z_load

3. Operational Amplifiers:
   - Inverting Amplifier: V_out = - (R_f/R_in) V_in
   - Non-Inverting Amplifier: V_out = (1 + R_f/R_in) V_in
   - Integrator: V_out = -1/(RC) ∫ V_in dt
   - Differentiator: V_out = -RC dV_in/dt

Two-Port Networks

1. Z-Parameters (Impedance Parameters):
   - V1 = Z11I1 + Z12I2
   - V2 = Z21I1 + Z22I2

2. Y-Parameters (Admittance Parameters):
   - I1 = Y11V1 + Y12V2
   - I2 = Y21V1 + Y22V2

3. h-Parameters (Hybrid Parameters):
   - V1 = h11I1 + h12V2
   - I2 = h21I1 + h22V2

4. g-Parameters (Inverse Hybrid Parameters):
   - I1 = g11V1 + g12I2
   - V2 = g21V1 + g22I2

5. ABCD-Parameters (Transmission Parameters):
   - V1 = AV2 + BI2
   - I1 = CV2 + DI2
  
