2025-02-10 12:30
Status: 
Tags: [[Power Series II]]
# proof of addition formula for cos(x+y)

TD: YEAR1::TERM2::MA139 Analysis 2::03 Power Series II
Q: Prove the addition formula for $\cos(x+y)$
A: For a fixed $z$ let $f(x) = \cos x \cos(z - x) - \sin x \sin(z - x).$  
It is easy to check that $f'(x) = 0$ for all $x$ and so by MVT $f$ is constant.  
When $x = 0$ we have $f(0) = \cos 0 \cos z - \sin 0 \sin z = \cos z.$ 
Hence $f(x) = \cos z$ for all $x$. Now if we set $z = x + y$ we get $\cos x \cos y - \sin x \sin y = f(x) = \cos z = \cos(x + y).$ as required.

