# hw_lineareqs

## Contents

<div>
  
*   [Problem 1 (in-class)](#1)
*   [Problem23 (in-class?)](#3)

</div>

## Problem 1 (in-class)<a name="1"></a>

Consider the linear mass-spring system shown.  All masses and natural (i.e. unstretched) spring lengths are equal, but the spring constants vary as indicated. The top spring is attached at *y* = 1.5 m and the +*y*-direction is upward.

<img src="https://github.com/bethel-physics/hw_lineareqs/blob/master/Springs0.png" width=300 />

 * **On paper**, write expressions for the equilibrium conditions for each mass.
 * Define your matrix *A* and the right-hand-side vector *b* for the linear system *Ay* = *b* describing the mass-spring system.
 * Determine the equilibrium positions *y* for each mass using the MATLAB command, *x* = inv(*A*)*b*
 
## Problem 2 (in-class?)<a name="3"></a>

(From *Garcia*, #6 page 115) Using Kirchhoff's laws in circuit problems involves solving a set of simultaneous equations. Consider the simple circuit shown.

![Problem 3](Circuit.gif)

 * Write a program that computes the currents, given the resistances and voltages as inputs. 
 * Have your program produce a graph of the power delivered to R<sub>5</sub> as a function of V<sub>2</sub>
 * Use this range of values for V<sub>2</sub>: 0 -- 20 V
 * Use R<sub>1</sub> = R<sub>2</sub> = 1 Ω, R<sub>3</sub> = R<sub>4</sub> = 2 Ω, R<sub>5</sub> = 5 Ω, V<sub>1</sub> = 2 V, V<sub>3</sub> = 5 V.
 
Important equations:
 * Kirchhoff's loop rule: ΔV = 0 over any loop
 * Kirchhoff's junction rule: net current flowing into a junction = net current flowing out of the junction
 * Power delivered to a resistor: P = I<sup>2</sup>R
