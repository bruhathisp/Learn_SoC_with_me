1. Current is a vector quantity https://youtu.be/g7DKec-IzoQ?feature=shared
Sure, here’s an extensive list of formulas for network theory in electricity, ranging from basic concepts to advanced topics:

### Basic Concepts

1. **Electric Charge:**
   - \( Q = ne \) (where \( n \) is the number of electrons, \( e \) is the elementary charge)

2. **Law of Conservation of Charge:**
   - Total charge before a process = Total charge after the process

3. **Electric Current:**
   - \( I = \frac{dQ}{dt} \) (where \( Q \) is the charge, \( t \) is time)

4. **Conventional Current vs. Electron Current:**
   - Conventional current flows from positive to negative, whereas electron flow is from negative to positive.

5. **Electric Potential Difference (Voltage):**
   - \( V = W/Q \) (where \( W \) is work done, \( Q \) is charge)

6. **Electric Power:**
   - \( P = VI \)
   - \( P = I^2R \)
   - \( P = \frac{V^2}{R} \)

### Circuit Elements

1. **Resistor:**
   - \( V = IR \)

2. **Ohm’s Law:**
   - \( V = IR \)
   - \( I = \frac{V}{R} \)
   - \( R = \frac{V}{I} \)

3. **Inductor:**
   - \( V_L = L \frac{dI}{dt} \)
   - Energy Stored: \( E = \frac{1}{2} L I^2 \)

4. **Capacitor:**
   - \( Q = CV \)
   - \( I = C \frac{dV}{dt} \)
   - Energy Stored: \( E = \frac{1}{2} CV^2 \)

### Series and Parallel Combinations

1. **Series Resistors:**
   - \( R_{total} = R_1 + R_2 + \cdots + R_n \)

2. **Parallel Resistors:**
   - \( \frac{1}{R_{total}} = \frac{1}{R_1} + \frac{1}{R_2} + \cdots + \frac{1}{R_n} \)

3. **Series Capacitors:**
   - \( \frac{1}{C_{total}} = \frac{1}{C_1} + \frac{1}{C_2} + \cdots + \frac{1}{C_n} \)

4. **Parallel Capacitors:**
   - \( C_{total} = C_1 + C_2 + \cdots + C_n \)

5. **Series Inductors:**
   - \( L_{total} = L_1 + L_2 + \cdots + L_n \)

6. **Parallel Inductors:**
   - \( \frac{1}{L_{total}} = \frac{1}{L_1} + \frac{1}{L_2} + \cdots + \frac{1}{L_n} \)

### Kirchhoff’s Laws

1. **Kirchhoff’s Current Law (KCL):**
   - \( \sum I_{in} = \sum I_{out} \)

2. **Kirchhoff’s Voltage Law (KVL):**
   - \( \sum V = 0 \) (around a closed loop)

### AC Circuits

1. **Impedance:**
   - Resistor: \( Z_R = R \)
   - Inductor: \( Z_L = j\omega L \)
   - Capacitor: \( Z_C = \frac{1}{j\omega C} \)

2. **Reactance:**
   - Inductive Reactance: \( X_L = \omega L \)
   - Capacitive Reactance: \( X_C = \frac{1}{\omega C} \)

3. **Phasor Relationships:**
   - \( V_R = IR \)
   - \( V_L = I(j\omega L) \)
   - \( V_C = I \left(\frac{1}{j\omega C}\right) \)

4. **Power in AC Circuits:**
   - Apparent Power: \( S = VI^* \) (where \( I^* \) is the complex conjugate of \( I \))
   - Real Power: \( P = VI \cos(\theta) \)
   - Reactive Power: \( Q = VI \sin(\theta) \)
   - Power Factor: \( \text{pf} = \cos(\theta) \)

### Network Theorems

1. **Superposition Theorem:**
   - Total response in any element is the sum of the responses caused by each independent source acting alone.

2. **Thevenin’s Theorem:**
   - Any network can be replaced by an equivalent voltage source \( V_{th} \) in series with a resistance \( R_{th} \).

3. **Norton’s Theorem:**
   - Any network can be replaced by an equivalent current source \( I_N \) in parallel with a resistance \( R_N \).

4. **Maximum Power Transfer Theorem:**
   - Maximum power is delivered to the load when \( R_L = R_{th} \).

### Advanced Topics

1. **Laplace Transform:**
   - \( V(s) = \mathcal{L}\{v(t)\} \)
   - \( I(s) = \mathcal{L}\{i(t)\} \)
   - Impedance in s-domain:
     - Resistor: \( Z_R(s) = R \)
     - Inductor: \( Z_L(s) = sL \)
     - Capacitor: \( Z_C(s) = \frac{1}{sC} \)

2. **Transfer Functions:**
   - \( H(s) = \frac{V_{out}(s)}{V_{in}(s)} \)

3. **State-Space Analysis:**
   - State Equations: \( \dot{x}(t) = Ax(t) + Bu(t) \)
   - Output Equation: \( y(t) = Cx(t) + Du(t) \)

4. **Fourier Series and Fourier Transform:**
   - Fourier Series: \( f(t) = \sum_{n=-\infty}^{\infty} C_n e^{j n \omega_0 t} \)
   - Fourier Transform: \( F(\omega) = \int_{-\infty}^{\infty} f(t) e^{-j \omega t} dt \)

5. **Bode Plot:**
   - Magnitude Plot: \( 20 \log_{10}|H(j\omega)| \)
   - Phase Plot: \( \angle H(j\omega) \)

6. **Nyquist Plot:**
   - Plot of \( H(j\omega) \) on the complex plane as \( \omega \) varies from \(-\infty\) to \(\infty\).

7. **Root Locus:**
   - Graphical representation of the roots of the characteristic equation of a control system as a system parameter is varied.

### Network Analysis Techniques

1. **Mesh Analysis:**
   - Use KVL to write equations for each mesh (independent loop).
   - Solve the resulting system of linear equations to find mesh currents.

2. **Nodal Analysis:**
   - Use KCL to write equations for each node (excluding reference node).
   - Solve the resulting system of linear equations to find node voltages.

### Specialized Components and Circuits

1. **RLC Circuits:**
   - Series RLC Circuit: \( Z = R + j\left(\omega L - \frac{1}{\omega C}\right) \)
   - Parallel RLC Circuit: \( Y = G + j\left(\omega C - \frac{1}{\omega L}\right) \)

2. **Transformers:**
   - Turns Ratio: \( \frac{N_1}{N_2} = \frac{V_1}{V_2} = \frac{I_2}{I_1} \)
   - Impedance Reflection: \( Z_{in} = \left(\frac{N_1}{N_2}\right)^2 Z_{load} \)

3. **Operational Amplifiers:**
   - Inverting Amplifier: \( V_{out} = -\left(\frac{R_f}{R_{in}}\right) V_{in} \)
   - Non-Inverting Amplifier: \( V_{out} = \left(1 + \frac{R_f}{R_{in}}\right) V_{in} \)
   - Integrator: \( V_{out} = -\frac{1}{R C} \int V_{in} \, dt \)
   - Differentiator: \( V_{out} = -R C \frac{dV_{in}}{dt} \)

### Two-Port Networks

1. **Z-Parameters (Impedance Parameters):**
   - \( V_1 = Z_{11}I_1 + Z_{12}I_2 \)
   - \( V_2 = Z_{21}I_1 + Z_{22}I_2 \)

2. **Y-Parameters (Admittance Parameters):**
   - \( I_1 = Y_{11}V_1 + Y_{12}V_2 \)
   - \( I_2 = Y_{21}V_1 + Y_{22}V_2 \)

3. **h-

Parameters (Hybrid Parameters):**
   - \( V_1 = h_{11}I_1 + h_{12}V_2 \)
   - \( I_2 = h_{21}I_1 + h_{22}V_2 \)

4. **g-Parameters (Inverse Hybrid Parameters):**
   - \( I_1 = g_{11}V_1 + g_{12}I_2 \)
   - \( V_2 = g_{21}V_1 + g_{22}I_2 \)

5. **ABCD-Parameters (Transmission Parameters):**
   - \( V_1 = AV_2 + BI_2 \)
   - \( I_1 = CV_2 + DI_2 \)

This extensive list covers a wide range of formulas and concepts in network theory for electricity. If you need further elaboration or additional topics, feel free to ask!
