2025-02-20 21:45
Status: 
Tags: [[Integration with special coordinates]]
# cylindrical coordinates example 2 (cone)

TD: YEAR1::TERM2::MA144 Modelling 2::06 Integration with special coordinates
Q: Find the volume of a cone (turned upside down) with base radius $a$ and height $h$.
A: when $z=h$, the desired radius is $a$, so you want
$$x^{2}+y^{2}=\left( \frac{az}{h} \right)^{2}$$
so rearranging this we get $z=\frac{hr}{a}$, and our integral is $$
\int\limits_0^{2\pi} \int\limits_0^a \int\limits_{\frac{hr}{a}}^h r \, \mathrm{d}z \, \mathrm{d}r \, \mathrm{d}\theta
$$which is evaluated to equal $\frac{1}{3}\pi a^{2}h$
<!--ID: 1740088463811-->

