# Problem 1: Superposition Theorem

**Question:** Find the value of voltage \( V_2 \) across \( R_2 \) using the superposition theorem in the following circuit:

**Given:**
- Voltage source \( V_1 = 12V \)
- Current source \( I = 3A \)
- Resistor \( R_1 = 6\Omega \)
- Resistor \( R_2 = 8\Omega \)

### Solution:

The superposition theorem states that in a linear circuit with multiple sources, the voltage or current in any component of the circuit is the algebraic sum of the voltages or currents produced by each source acting independently, with all other sources replaced by their internal resistances.

1. **Consider the voltage source \( V_1 = 12V \) alone:**
   - Replace the current source with an open circuit (since an ideal current source has infinite resistance when open).
   - The circuit becomes a simple series circuit with \( R_1 \) and \( R_2 \).

   Equivalent resistance:
   \[ R_{eq} = R_1 + R_2 = 6\Omega + 8\Omega = 14\Omega \]

   Current through the circuit from the voltage source:
   \[ I_{V1} = \frac{V_1}{R_{eq}} = \frac{12V}{14\Omega} = 0.857A \]

   Voltage across \( R_2 \) due to the voltage source:
   \[ V_{R_2(V1)} = I_{V1} \times R_2 = 0.857A \times 8\Omega = 6.857V \]

2. **Consider the current source \( I = 3A \) alone:**
   - Replace the voltage source with a short circuit (since an ideal voltage source has zero internal resistance when shorted).
   - In this case, the current divides between \( R_1 \) and \( R_2 \).

   Since the current \( I = 3A \) flows through the parallel combination of \( R_1 \) and \( R_2 \), the voltage across \( R_2 \):
   \[ V_{R_2(I)} = I \times R_2 = 3A \times 8\Omega = 24V \]

3. **Apply the superposition principle:**
   - The total voltage across \( R_2 \) is the sum of the voltages from each source:
     \[ V_2 = V_{R_2(V1)} + V_{R_2(I)} = 6.857V + 24V = 30.857V \]

Thus, the voltage across \( R_2 \) using the superposition theorem is 30.857 V.
