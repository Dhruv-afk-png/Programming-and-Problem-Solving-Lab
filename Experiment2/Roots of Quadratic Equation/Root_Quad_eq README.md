
## Problem Statement
Write a program to find the roots of a quadratic equation, given its coefficients a, b, and c. Use the quadratic formula: 
(-b+-root(b**2-4ac))/2a.

---

## Algorithm
1. Start.  
2. Read the coefficients a, b, and c.
3. Calculate the discriminant using:-
𝐷=𝑏^2
−
4
𝑎
𝑐
D=b
2
−4ac

If D > 0

Compute

𝑥
1
=
−
𝑏
+
𝐷
2
𝑎
,
𝑥
2
=
−
𝑏
−
𝐷
2
𝑎
x
1
	​

=
2a
−b+
D
	​

	​

,x
2
	​

=
2a
−b−
D
	​

	​


Display two real and distinct roots

Else if D = 0

Compute

𝑥
=
−
𝑏
2
𝑎
x=
2a
−b
	​


Display equal real roots

Else (D < 0)

Compute

Real part
=
−
𝑏
2
𝑎
Real part=
2a
−b
	​

Imaginary part
=
−
𝐷
2
𝑎
Imaginary part=
2a
−D
	​

	​


Display complex roots

Stop
---

## Flowchart
![Flowchart](Area_Of_Triangle.drawio.png)

---

## Execution
<p align="center">
  <img src="Area_Of_Triangle Execution.png" width="900">
</p>



