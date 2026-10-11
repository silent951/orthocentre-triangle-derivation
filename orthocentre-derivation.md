# Orthocentre Formula: Complete Step-by-Step Derivation

**By Dhivaan K**

## 1. Given equations

The pair of lines through the origin is represented by the homogeneous equation
\[
Ax^2+2Hxy+By^2=0. \tag{1}
\]
The third side of the triangle is
\[
Lx+My+N=0. \tag{2}
\]
Let the slopes of the two lines represented by (1) be \(m_1\) and \(m_2\). Their equations are
\[
y=m_1x,\qquad y=m_2x.
\]
The triangle's vertices are the origin \(O=(0,0)\), the intersection \(P_1\) of \(y=m_1x\) with (2), and the intersection \(P_2\) of \(y=m_2x\) with (2). Let the orthocentre be \(K=(h,k)\).

## 2. Relations between the two slopes

Substitute \(y=mx\) into (1):
\[
Ax^2+2Hx(mx)+B(mx)^2=0.
\]
Expand:
\[
Ax^2+2Hmx^2+Bm^2x^2=0.
\]
Factor out \(x^2\):
\[
x^2(A+2Hm+Bm^2)=0.
\]
For the two line directions, the slope equation is
\[
Bm^2+2Hm+A=0.
\]
Its roots are \(m_1\) and \(m_2\). By the sum and product of roots,
\[
m_1+m_2=-\frac{2H}{B}, \tag{3}
\]
and
\[
m_1m_2=\frac{A}{B}. \tag{4}
\]

## 3. Find the coordinates of \(P_1\) and \(P_2\)

For \(P_1\), use \(y=m_1x\) in the third line (2):
\[
Lx+M(m_1x)+N=0.
\]
Combine the terms containing \(x\):
\[
(L+Mm_1)x+N=0.
\]
Move \(N\) to the right:
\[
(L+Mm_1)x=-N.
\]
Divide:
\[
x_1=-\frac{N}{L+Mm_1}.
\]
Since \(y_1=m_1x_1\),
\[
y_1=m_1\left(-\frac{N}{L+Mm_1}\right)
=-\frac{Nm_1}{L+Mm_1}.
\]
Therefore,
\[
P_1=\left(-\frac{N}{L+Mm_1},-\frac{Nm_1}{L+Mm_1}\right). \tag{5}
\]

For \(P_2\), use \(y=m_2x\) in (2):
\[
Lx+M(m_2x)+N=0,
\]
\[
(L+Mm_2)x+N=0,
\]
\[
(L+Mm_2)x=-N,
\]
\[
x_2=-\frac{N}{L+Mm_2}.
\]
Then
\[
y_2=m_2x_2
=m_2\left(-\frac{N}{L+Mm_2}\right)
=-\frac{Nm_2}{L+Mm_2}.
\]
Therefore,
\[
P_2=\left(-\frac{N}{L+Mm_2},-\frac{Nm_2}{L+Mm_2}\right). \tag{6}
\]

## 4. Equation of the altitude through \(P_1\)

The side \(OP_2\) has slope \(m_2\). A line perpendicular to it has slope
\[
-\frac{1}{m_2}.
\]
The altitude through \(P_1=(x_1,y_1)\) is therefore
\[
y-y_1=-\frac{1}{m_2}(x-x_1).
\]
Multiply both sides by \(m_2\):
\[
m_2(y-y_1)=-(x-x_1).
\]
Expand:
\[
m_2y-m_2y_1=-x+x_1.
\]
Bring \(x\) and \(m_2y_1\) to the appropriate sides:
\[
x+m_2y=x_1+m_2y_1.
\]
Now substitute the coordinates from (5):
\[
x+m_2y=-\frac{N}{L+Mm_1}
+m_2\left(-\frac{Nm_1}{L+Mm_1}\right).
\]
Write the second term as one fraction:
\[
x+m_2y=-\frac{N}{L+Mm_1}
-\frac{Nm_1m_2}{L+Mm_1}.
\]
Combine the fractions:
\[
x+m_2y=-\frac{N+Nm_1m_2}{L+Mm_1}.
\]
Factor out \(N\) in the numerator:
\[
x+m_2y=-\frac{N(1+m_1m_2)}{L+Mm_1}. \tag{7}
\]

## 5. Equation of the altitude through \(P_2\)

The side \(OP_1\) has slope \(m_1\). The altitude through \(P_2\), perpendicular to \(OP_1\), has slope \(-1/m_1\):
\[
y-y_2=-\frac{1}{m_1}(x-x_2).
\]
Multiply by \(m_1\):
\[
m_1(y-y_2)=-(x-x_2).
\]
Expand:
\[
m_1y-m_1y_2=-x+x_2.
\]
Rearrange:
\[
x+m_1y=x_2+m_1y_2.
\]
Substitute the coordinates from (6):
\[
x+m_1y=-\frac{N}{L+Mm_2}
+m_1\left(-\frac{Nm_2}{L+Mm_2}\right).
\]
Expand the product:
\[
x+m_1y=-\frac{N}{L+Mm_2}
-\frac{Nm_1m_2}{L+Mm_2}.
\]
Combine:
\[
x+m_1y=-\frac{N+Nm_1m_2}{L+Mm_2}.
\]
Factor:
\[
x+m_1y=-\frac{N(1+m_1m_2)}{L+Mm_2}. \tag{8}
\]

## 6. Solve the two altitude equations for \(k\)

At the orthocentre \(K=(h,k)\), equations (7) and (8) give
\[
h+m_2k=-\frac{N(1+m_1m_2)}{L+Mm_1}, \tag{9}
\]
\[
h+m_1k=-\frac{N(1+m_1m_2)}{L+Mm_2}. \tag{10}
\]
Subtract (10) from (9):
\[
(h+m_2k)-(h+m_1k)
=-\frac{N(1+m_1m_2)}{L+Mm_1}
+\frac{N(1+m_1m_2)}{L+Mm_2}.
\]
On the left, \(h-h=0\), so
\[
(m_2-m_1)k
=-\frac{N(1+m_1m_2)}{L+Mm_1}
+\frac{N(1+m_1m_2)}{L+Mm_2}.
\]
Factor out \(N(1+m_1m_2)\):
\[
(m_2-m_1)k
=N(1+m_1m_2)\left(
\frac{1}{L+Mm_2}-\frac{1}{L+Mm_1}
\right).
\]
Use a common denominator inside the brackets:
\[
\frac{1}{L+Mm_2}-\frac{1}{L+Mm_1}
=\frac{(L+Mm_1)-(L+Mm_2)}
{(L+Mm_2)(L+Mm_1)}.
\]
Expand the numerator:
\[
(L+Mm_1)-(L+Mm_2)
=L+Mm_1-L-Mm_2
=M(m_1-m_2).
\]
Thus,
\[
(m_2-m_1)k
=N(1+m_1m_2)
\frac{M(m_1-m_2)}
{(L+Mm_1)(L+Mm_2)}.
\]
Since \(m_1-m_2=-(m_2-m_1)\),
\[
(m_2-m_1)k
=-\frac{NM(1+m_1m_2)(m_2-m_1)}
{(L+Mm_1)(L+Mm_2)}.
\]
Divide both sides by \(m_2-m_1\):
\[
\boxed{k=-\frac{NM(1+m_1m_2)}
{(L+Mm_1)(L+Mm_2)}}. \tag{11}
\]

## 7. Solve for \(h\)

Use equation (9):
\[
h+m_2k=-\frac{N(1+m_1m_2)}{L+Mm_1}.
\]
Move \(m_2k\) to the right:
\[
h=-\frac{N(1+m_1m_2)}{L+Mm_1}-m_2k.
\]
Substitute (11):
\[
h=-\frac{N(1+m_1m_2)}{L+Mm_1}
+m_2\frac{NM(1+m_1m_2)}
{(L+Mm_1)(L+Mm_2)}.
\]
Write the first term with the common denominator:
\[
h=-\frac{N(1+m_1m_2)(L+Mm_2)}
{(L+Mm_1)(L+Mm_2)}
+\frac{NMm_2(1+m_1m_2)}
{(L+Mm_1)(L+Mm_2)}.
\]
Combine the numerators:
\[
h=\frac{-N(1+m_1m_2)(L+Mm_2)
+NMm_2(1+m_1m_2)}
{(L+Mm_1)(L+Mm_2)}.
\]
Factor out \(-N(1+m_1m_2)\):
\[
h=-\frac{N(1+m_1m_2)[(L+Mm_2)-Mm_2]}
{(L+Mm_1)(L+Mm_2)}.
\]
Simplify the bracket:
\[
(L+Mm_2)-Mm_2=L.
\]
Therefore,
\[
\boxed{h=-\frac{NL(1+m_1m_2)}
{(L+Mm_1)(L+Mm_2)}}. \tag{12}
\]

## 8. Rewrite the answer using \(A,H,B,L,M,N\)

Define
\[
D=(L+Mm_1)(L+Mm_2).
\]
Expand the product:
\[
D=L^2+LMm_2+LMm_1+M^2m_1m_2.
\]
Group the middle terms:
\[
D=L^2+LM(m_1+m_2)+M^2m_1m_2.
\]
Use the root relations (3) and (4):
\[
D=L^2+LM\left(-\frac{2H}{B}\right)
+M^2\left(\frac{A}{B}\right).
\]
So
\[
D=L^2-\frac{2HLM}{B}+\frac{AM^2}{B}.
\]
Write all terms over the denominator \(B\):
\[
D=\frac{BL^2}{B}-\frac{2HLM}{B}+\frac{AM^2}{B}.
\]
Combine:
\[
D=\frac{BL^2-2HLM+AM^2}{B}.
\]
Let
\[
Q=BL^2-2HLM+AM^2.
\]
Then
\[
\boxed{D=\frac{Q}{B}}. \tag{13}
\]

Also, from (4),
\[
1+m_1m_2=1+\frac{A}{B}.
\]
Write \(1\) with denominator \(B\):
\[
1+m_1m_2=\frac{B}{B}+\frac{A}{B}.
\]
Therefore,
\[
\boxed{1+m_1m_2=\frac{A+B}{B}}. \tag{14}
\]

Substitute (13) and (14) into (12):
\[
h=-\frac{NL\left(\frac{A+B}{B}\right)}{\frac{Q}{B}}.
\]
Dividing by a fraction means multiplying by its reciprocal:
\[
h=-\frac{NL(A+B)}{B}\cdot\frac{B}{Q}.
\]
Cancel \(B\):
\[
\boxed{h=-\frac{NL(A+B)}{Q}}.
\]

Now substitute (13) and (14) into (11):
\[
k=-\frac{NM\left(\frac{A+B}{B}\right)}{\frac{Q}{B}}.
\]
Multiply by the reciprocal:
\[
k=-\frac{NM(A+B)}{B}\cdot\frac{B}{Q}.
\]
Cancel \(B\):
\[
\boxed{k=-\frac{NM(A+B)}{Q}}.
\]

## 9. Final formula

With
\[
Q=BL^2-2HLM+AM^2,
\]
the orthocentre is
\[
\boxed{
K=(h,k)=\left(
-\frac{NL(A+B)}{BL^2-2HLM+AM^2},
-\frac{NM(A+B)}{BL^2-2HLM+AM^2}
\right).
}
\]

## 10. Check the altitude from the origin

The third side is
\[
Lx+My+N=0.
\]
Its normal vector is \((L,M)\), so a direction vector along the line is \((M,-L)\). A perpendicular direction is therefore \((L,M)\). Hence the altitude from the origin has equation
\[
My-Lx=0.
\]
Check whether \(K=(h,k)\) satisfies it:
\[
Lk-Mh
=L\left(-\frac{NM(A+B)}{Q}\right)
-M\left(-\frac{NL(A+B)}{Q}\right).
\]
Multiply:
\[
Lk-Mh=-\frac{LNM(A+B)}{Q}
+\frac{MNL(A+B)}{Q}.
\]
The two terms cancel:
\[
\boxed{Lk-Mh=0}.
\]
So the derived point lies on the altitude from the origin as required.

## 11. Conditions for this derivation

This slope-based proof assumes:
- \(B\ne0\), so the quadratic equation for the slopes has a nonzero leading coefficient.
- \(m_1\) and \(m_2\) are finite and distinct.
- \(L+Mm_1\ne0\) and \(L+Mm_2\ne0\), so the intersections with the third line have finite coordinates as written.
- \(Q\ne0\), so the displayed formula has a nonzero denominator.

Special or degenerate configurations may need a separate treatment.

## About the learning process

I’m Dhivaan K, a student learning mathematics with AI as a study partner. I use AI to explore ideas, ask questions, check reasoning, and work through calculations step by step. These notes reflect a learning process: understanding the method, checking each algebraic step, and making the reasoning clear enough for another student to follow. AI can help explain and review, but I remain responsible for questioning, verifying, and understanding the mathematics. My goal is to learn with AI—not simply copy an answer.
