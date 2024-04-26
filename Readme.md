Example: A model of a wave moving into three different states is described in the figure below. 
         The first image is labeled with t=0, although the movement started earlier, because at 
         this point the timer has started counting down. Determine the following? <br />
a. Wave speed and period. <br />
b. Wavelength and frequency. <br />
c. Mathematical expression for wave. <br />
d. Total energy. <br />
<br />
Solution: 

<image align="right" alt="Milad" width = "400" src="http://up44.ir/previews/22c49fce44f1ef0d0da2aa19955575bc.jpg"> 
    
<pre>import math     # library of python for calculate 
                  the calculation of below <br />
T = 0.55             # Period time 
L = 4                # lenght 
V_w = T / L          # wave velocity <br />
print(f"V_w = {V_w:.4f}") 
<br />
g = 32.2             # gravity 
π = 3.14             # pi number <br />
L_w = ((2 * π * V_w * V_w) / g)         # wave lenght 
T_w = math.sqrt((2 * π * L_w) / g)      # period time 
f_w = 1 / T_w        # frequency wave 
k = 2 * π / L_w <br />
print(f"L_w = {L_w:0.4f}") 
print(f"T_w = {T_w:0.4f}") 
print(f"f_w = {f_w:0.4f}") 
print(f"k = {k:0.4f}") 
<br />
ζ_a = 0.3            # amplitude 
p = 1.9905
E = 0.5 * p * g * ζ_a * ζ_a * L_w      # Total energy <br />
print(f"E = {E:0.4f}")

ω = 4.49 

for x in range(21):  # Assuming x ranges from 0 to 20 
        ζ_0 = ζ_a * math.sin(k * x - ω * t) 
        print(f"ζ_0 at t={t:.1f}, x={x}: {ζ_0:.4f}") <br />
