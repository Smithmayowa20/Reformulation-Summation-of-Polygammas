# Reformulation-Summation-of-Polygammas
Summation of Polygamma functions at negative integer values












Reformulation: Summation of Some Polygamma Functions at Negative Integer Values

By Alli-Smith Mayowa










#ABSTRACT



In this paper we consider the summation of some Polygamma[n, f(x)] function from interval x equals to N_1 to interval x equals to N_2, where the value of f(x) along this interval includes some negative or asymptotically negative integer values. We also consider a normalized signal function that is continous and differentiable across all real domain unlike the sinc(x) function.





#OUTLINE



1). Introduction 

2). Gamma & Polygamma Function

3). Np-Completeness

4). Continuous CoSinc Function 

5). Conclusion

6). References




























#INTRODUCTION



Closed form partial summations of some elementary and non-elementary mathematical functions f(x,y) tend to resolve into non-polynomial functions comprising of the Polygamma, Factorial and other closely related functions g(y). These new functions when their x values are positive can be approximated by Maclaurin, Taylor and other series expansion methods at a specific value or at infinity. At negative values of x these functions can be expressed in terms of their positive values, and the co-tangent function or closely associated functions, which tend to positive or negative infinity at some or all integer values and that are discontinuous.

Let f(x,y) = 1/(x + y)

Sum[f(x,y), {x, 1, N}, {y, 1, N}] = Sum[Polygamma[1,y], {y, 1, N}] - Expression(1)

Where; g(y) = Polygamma[1,y]


Let f_a(x,y) = 1/(x - y)

Sum[f_a(x,y), {x, 1, N}, {y, 1, N}] = Sum[Polygamma[1, -y], {y, 1, N}] - Expression(2)

Where; g_a(y) = Polygamma[1,-y]


Expression(1) & Expression(2) above are both very simple cases of functions f(x), which when partially summed resolve into new functions g(y) comprising or wholly composed of Polygamma functions with positive variables and Polygamma functions with negative variables respectively.











#GAMMA & POLYGAMMA FUNCTION



Let g(y) = Polygamma[1,y]

Taylor Series Expansion of g(y) at infinity = 


Let g_a(y) = Polygamma[1,-y]

g_a (y) = Polygamma[1,y] + 1/y + (Pi * y * Cot[Pi * y])





#CONTINOUS COSINC FUNCTION 



Cos(F * Sin^2(Pi x))/((F * Sin^2(Pi x)) + 1)

Let F(x) = 1/(F * Sin**2(Pi * (d - x)/x) + 1)

R_F(x) = Integrate(BernoulliB(2,Frac(x)) * D(F(x), (x,2)) * 1/2, ())

local minimum g(x) of f(x) = 1/(1 + 4n), where d = 21 and F = 10**5

We can utilize these points from g(x) above as intervals for R_F(x) integration.

Integrate(R_F(1/(1 + 4n)), (n,1,2)) + Integrate(R_F(1/(1 + 4n)), (n,2,3)) + .... + Integrate(R_F(1/(1 + 4n)), (n,k-1,k))

Integrate(Taylor Series(R_F(1/(1 + 4n)),(n=)), (n,1,2)) + .... + Integrate(Taylor Series(R_F(1/(1 + 4n)),( n=(1/(1 + 4(k - 1)) + (1/(1 + 4k)))/2 )), (n,k-1,k))

Sum(Integrate(Taylor Series(R_F(1/(1 + 4n)), n=(1/(1 + 4(J-1)) + 1/(1 + 4J))/2), (n,J-1,J)),(J,1,k))





#ACKNOWLEDGEMENT



I would like to thank, appreciate, revere, and worship Lord God Almighty, for helping me with the knowledge and guidance for this research paper. Without whom we can't even lift a pen to paper, thoughtless of forming and expressing our thoughts via words.










#CONCLUSION 



In conclusion











#REFERENCES



1).

