2025-02-10 13:08
Status: 
Tags: [[Power Series II]]
# proof of addition formula for sin(x+y)

TD: YEAR1::TERM2::MA139 Analysis 2::03 Power Series II
Q: Prove the addition formula for $\sin(x+y)$
A: For a fixed $z$ let $f(x) = \sin x \cos(z - x) + \cos x \sin(z - x).$  
It is easy to check that $f'(x) = 0$ for all $x$ and so by MVT $f$ is constant.  
When $x = 0$ we have $f(0) = \cos 0 \sin z + \cos 0 \sin z = \sin z.$ 
Hence $f(x) = \cos z$ for all $x$. Now if we set $z = x + y$ we get $\sin x \cos y + \cos x \sin y = f(x) = \sin z = \sin(x + y).$ as required.
<!--ID: 1739193137066-->
