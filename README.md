# hw_lineareqs

## Contents

<div>
  
*   [Problem 1 (homework)](#2)
*   [Problem 2 (homework)](#3)

</div>

## Problem 1 (homework)<a name="2"></a>

Consider the linear mass-spring system shown. All masses (*m* = 0.5 kg), natural spring lengths (*L<sub>0</sub>* = 0.25 m), and spring constants (*k* = 100 N/m) are equal. The top spring is attached to a rigid object at height *y* = 1.5m and the bottom spring is attached at height *y* = 0.0m. Masses 2 and 4 are coupled by an additional spring, with the same natural length and spring constant as the other springs.

![Problem 1](Springs.gif)

 * Derive the system of equations that must be solved to determine the equilibrium positions for each mass
 * Express the linear system in the form <b>Ax = b</b>
 * Write a program to determine the equilibrium positions of the masses
 
## Problem 2 (homework)<a name="3"></a>

(From *Garcia*, #6 page 115) Using Kirchhoff's laws in circuit problems involves solving a set of simultaneous equations. Consider the simple circuit shown.

![Problem 2](Circuit.gif)

 * Write a program that computes the currents, given the resistances and voltages as inputs. 
 * Have your program produce a graph of the power delivered to R<sub>5</sub> as a function of V<sub>2</sub>
 * Use this range of values for V<sub>2</sub>: 0 -- 20 V
 * Use R<sub>1</sub> = R<sub>2</sub> = 1 Ω, R<sub>3</sub> = R<sub>4</sub> = 2 Ω, R<sub>5</sub> = 5 Ω, V<sub>1</sub> = 2 V, V<sub>3</sub> = 5 V.
 
Important equations:
 * Kirchhoff's loop rule: ΔV = 0 over any loop
 * Kirchhoff's junction rule: net current flowing into a junction = net current flowing out of the junction
 * Power delivered to a resistor: P = I<sup>2</sup>R
