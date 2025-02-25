2025-02-25 21:07
Status: 
Tags: [[Calculus of multivariable functions]]
# jacobian matrix example 2 (cylindrical coordinates)

TD: YEAR1::TERM2::MA144 Modelling 2::07 Calculus of multivariable functions.
Q: Calculate the Jacobian matrix and its determinant for the mapping $F$ defined by $F(r, \theta,z) = (r \cos \theta, r \sin \theta,z)$.
A: we know that $x=r\cos \theta$ and $y=r\sin \theta$ and $z=z$ so when we write out the Jacobian matrix we get $$
\underline{DF}(r,\theta)=\begin{pmatrix}
x_{r} & x_{\theta} & x_{z} \\
y_{r} & y_{\theta} & y_{z}  \\
z_{r} & z_{\theta} & z_{z}
\end{pmatrix}
=\begin{pmatrix}
\cos \theta & -r\sin \theta & 0\\
\sin \theta & r\cos \theta & 0 \\
0 & 0 & 1
\end{pmatrix}
$$then working out the determinant we get $$
\det \underline{DF}=r
$$which is as we expect from converting into cylindrical coordinates.
<!--ID: 1740518159768-->
