2025-02-25 21:10
Status: 
Tags: [[Calculus of multivariable functions]]
# jacobian matrix example 3 (spherical coordinates)

TD: YEAR1::TERM2::MA144 Modelling 2::07 Calculus of multivariable functions.
Q: Calculate the Jacobian matrix and its determinant for the mapping $F$ defined by $F(r, \theta,\phi) = (r \sin \phi \cos \theta, r \sin \phi \sin \theta,r\cos \phi)$.
A: we know that $x=r\sin \phi \cos \theta$,$y=r\sin \phi \sin \theta$ and $z=r\cos \phi$ so when we write out the Jacobian matrix we get $$
\begin{align}
\underline{DF}(r,\theta)&=\begin{pmatrix}
x_{r} & x_{\theta} & x_{\phi} \\
y_{r} & y_{\theta} & y_{\phi}  \\
z_{r} & z_{\theta} & z_{\phi}
\end{pmatrix} \\ \\
&=\begin{pmatrix}
\sin \phi \cos \theta & -r\sin \phi \sin \theta & r\cos \phi \cos \theta \\
\sin \phi \sin \theta &r\sin \phi \cos \theta &r\cos \phi \sin \theta \\
\cos \phi & 0 & -r\sin \theta
\end{pmatrix}
\end{align}
$$then working out the determinant we get $$
\det \underline{DF}=-r^{2}\sin \phi
$$which is as we expect from converting into spherical coordinates.
<!--ID: 1740518159756-->
