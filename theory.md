## Theory

  
This bridge is a modification of the maxwell's inductive and capacitive bridge. In this method, the self inductance is measured in terms of a standard capacitor. This method is applicable for precise measurement of self inductance over wide range of values. Figure 1 shows the circuit diagram of the bridge for balance conditions.
<p align="center">

![Rm501 Figure](images/anderson_bridge.jpg)

***Fig 1: Circuit diagram for Measurement of Self Inductance by Anderson's Bridge***
</p>
Let,

L<sub>1</sub>=Self inductance is to be measured.

R<sub>1</sub>= Resistance of self inductor.

r<sub>1</sub>= Resistance connected in series with self inductor.

r,R<sub>2</sub>,R<sub>3</sub>,R<sub>4</sub>= Known non inductive resistances.

C = Fixed standard capacitor.
       
At balance,  
<p align="center">
I<sub>1</sub>= I<sub>3</sub> and I<sub>2</sub>=I<sub>C</sub>+I<sub>4</sub>
</p>


now,
<p align="center">
  
$$ I_1R_3 =I_C/(j \omega C) \  then   I_C=I_1 j \omega CR_3...(1) $$
  
</p>

Writing the other balance equations,

<p align="center">
  
$$ I_1(r_1+R_1+j \omega L_1) = I_2R_2+rI_C...(2) $$
  
</p>
<p align="center">
$$ I_C(r+\frac{1}{j \omega C}) = (I_2-I_C)R_4 $$
</p>

Substituting the value of I<sub>C</sub> in equation (2) , we get
<p align="center">
  
$$ I_1(r_1+R_1+j \omega L_1) = I_2R_2+I_1 j \omega CrR_3 $$
  
</p>
or,
<p align="center">
$$ I_1(r_1+R_1+j \omega L_1-j \omega CrR_3) = I_2R_2...(3) $$
</p>
and
<p align="center">
  
$$ j \omega CR_3I_1(r+\frac{1}{j \omega C}) = (I_2-I_1j \omega CR_3)R_4 $$
  
</p>
or,
<p align="center">
$$ I_1(j \omega CrR_3+j \omega CR_3R_4) = I_2R_4...(4) $$
</p>


From equations (3) and (4) , we get by equating real and imaginary parts,
<p align="center">
  
$$ R_1 = \frac{R_2R_3}{R_4-r_1}...(5) $$
  
</p>
<p align="center">
  
$$ L_1 = C \frac{R_3}{R_4}[r(R_4+R_2)+R_2R_4]...(6) $$
  
</p>
An examination of balance equation reveals that to obtain easy convergence of balance , alternate adjustments of r<sub>1</sub> and r should be done as they appear in only equ. (1) and (2).
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
