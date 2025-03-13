1. trigonometric integration
	1.  $\int \sin^m{x} \cos^n{x} \, dx$
		- case: $m$ odd $\rightarrow$ use $u = \cos{x}$ substitution
		- case: $n$ odd $\rightarrow$ use $u = \sin x$ substitution
		- case: $m\, \& \,n$ even $\rightarrow$ reduce the degree by double angle formula
		1.  $\int \sin^3{x} \cos^2{x} \, dx$
			- = $\int \sin{x} \cos^2{x} (1 - \cos^2{x}) dx$
			- $u = \cos{x},\: du = -\sin{x} \,dx$
			- = $- \int u^2 (1- u^2)du$
			- = $- \int u^2 - u^4 du$
			- = $-\frac{u^3}{3} + \frac{u^5}{5} + C$
			- = $-\frac{\cos^3{x}}{3} + \frac{cos^5{x}}{5} + C$
		2.   $\int \sin^5{x} \cos^{\frac{3}{2}}{x} \, dx$
		3.   $\int \sin^2{x} \cos^3{x} \, dx$
		4.   $\int_{0}^{3\pi/2} \sin^5{x} \cos^2{x} \, dx$
		5.   $\int \sin^3{x} \cos^3{x} \, dx$
		6.   $\int \sin^{\frac{7}{2}}{x} \cos^3{x} \, dx$
		7.   $\int \sin^2{x} \cos^2{x} \, dx$
		8.   $\int \sin^4{x} \cos^2{x} \, dx$
		9.   $\int_0^{\pi/2} \cos^2{(3x)} \, dx$
		10.   $\int_{0}^{\pi/4} \sin^2{x} \, dx$
	2. $\int \tan^m{x} \sec^n{x} \, dx$
		- case: $n > 0$ even $\rightarrow$ use $u = \tan x$ substitution
			- case: $n > 0$ odd & $m$ odd (or $n$ even & $m$ odd) $\rightarrow$ use $u = \sec{x}$ substitution
		1. $\int \tan^2{x} \sec^4 {x} \, dx$
		2. $\int_{0}^{\pi/3} \tan^2{x} \sec^4 {x} \, dx$
		3. $\int \tan^3{x} \sec^4 {x} \, dx$
		4. $\int \tan{x} \sec^3{x} \, dx$
		5. $\int \tan^3{x} \sec^5 {x} \, dx$
		6. $\int_{0}^{\pi/4} \tan{x} \sec^5{x} \, dx$
		7. $\int \sec^3{x} \, dx$
		8. $\int \tan^2{x} \sec{x} \, dx$
		9. $\int \tan^5{x}\, dx$
		10. $\int_{0}^{\pi/3} \tan^3{x} \, dx$
2. trigonometric substitution
	- $\sqrt{a^2 -x^2}, x = a \sin{\theta}, dx = a \cos{\theta}, \sqrt{a^2 - x^2} = a \cos{\theta}$
	- $\sqrt{a^2 + x^2}, x = a \tan{\theta}, dx = a \sec^2{\theta}, \sqrt{a^2 + x^2} = a \sec{\theta}$
	- $\sqrt{x^2 - a^2}, x = a \sec {\theta}, dx = a \tan{\theta} \sec{\theta}, \sqrt{x^2 - a^2} = a \tan{\theta}$
	1. compute the following integrals
		1. $\int \frac{dx}{\sqrt{4-x^2}}$
			- $x = 2 \sin{\theta}, \, dx = 2\cos{\theta} \, d\theta$
			- =  $\int \frac{2\cos{\theta} \, d\theta}{\sqrt{4-(2 \sin{\theta})^2}}$
			- = $\int d\theta$
			- = $\theta + C$ 
			- = $\sin^{-1}(\frac{x}{2}) + C$
		2. $\int \frac{x^2}{\sqrt{4-x^2}}dx$
			- $x = 2\sin{\theta}, \, dx = 2\cos{\theta} \, d\theta$
			- = $\int \frac{(4 sin^2{\theta})(2 \cos{\theta} \, d\theta)}{\sqrt{4-(2\sin{\theta})^2}}$
			- = $\int 4 \sin^2{\theta} \, d\theta$
			- = $4\int \frac{1 - \cos{2\theta}}{2} \, d\theta$
			- = $2\theta - \sin{2 \theta} + C$
			- = $2\sin^{-1}(\frac{x}{2}) - 2\sin{\theta} \cos{\theta} + C$
			- $\cos{\theta} = \frac{\sqrt{4-x^2}}{2}$
			- =  $2\sin^{-1}(\frac{x}{2}) - 2\frac{x}{2} \frac{\sqrt{4-x^2}}{2} + C$
			- =  $2\sin^{-1}(\frac{x}{2}) - {x} \frac{\sqrt{4-x^2}}{2} + C$
		3. $\int_{0}^{7/\sqrt{2}} \frac{x^2}{\sqrt{49-x^2}}dx$
		4.  $\int \sqrt{5-4x^2}dx$
		5.  $\int \frac{\sqrt{x^2-9}}{x}dx \,(x > 3)$
		6.  $\int_{1}^{\sqrt{2}} x^3\sqrt{x^2-1} \,dx$
		7. $\int \sqrt{x^2+1} \,dx$
		8.  $\int_{1}^{\sqrt{3}} \frac{dx}{x^2\sqrt{x^2+1}}$
		9.  $\int \sqrt{7 + 4x +x^2} \,dx$
		10. $\int \sqrt{7 + 12x + 4x^2} \,dx$
		11. $\int \frac{x}{\sqrt{3 - 2x - x^2}} \,dx$
		12. $\int \frac{x^2 - 2x + 2}{\sqrt{x^2 - 2x + 10}} \,dx$
		13. $\int \frac{x}{\sqrt{3 + 2x - x^2}} \,dx$
		14. $\int_{0}^{1/2} \frac{x^3 \, dx}{(1 - x^2)^2}$
		15. $\int_{-3}^{3} \frac{dx}{\sqrt{x^2 + 9}}$
	2. verify that the area of a circle or radius $r$ is $\pi r^2$
	3. compute the length of the curve: $y = f(x) = \frac{x^2}{2}$ over the interval $[1, \sqrt{3}]$
3. partial fractions
	1. determine the proper form of th partial fractions for the following
		1. $\frac{1}{(x + 2)(x^2 - 4)(x^2 + x + 1)^2}$
		2. $\frac{x^3}{(x - 1)(x^3 - 1)(x^2 + 4x + 5)^2}$
		3. $\frac{x^7}{(x - 2)^2(x^2 - 4)(x^2 + 4)}$
	 2. compute the following integrals
		 1. $\int \frac{3x + 5}{(x-1)(x+3)} \, dx$
		 2. $\int \frac{x^2}{(x-1)^2} \, dx$
		 3. $\int \frac{x}{(x^2-1)(x-2)} \, dx$
		 4. $\int \frac{2x^3 + 3x^2 - 2x - 1}{(x^2 - 1)} \, dx$
		 5. $\int \frac{x + 2}{x^2 + 2x + 2} \, dx$
		 6. $\int \frac{x + 2}{(x - 1)^2(x^2 + 1)} \, dx$
		 7. $\int \frac{x^2 + x + 1}{x^3 + x} \, dx$
		 8. $\int \frac{x^2 |+ x + 2}{x^2 + 4x + 5} \, dx$
		 9. $\int \frac{7x^2 + 23x + 25}{x(x^2 + 4x + 5)} \, dx$
		 10. $\int \frac{5}{(x - 1)(x^2 + 2)} \, dx$
4. improper integral, convergent/divergent
	1. evaluate the following improper integrals
		1. $\int_{0}^{\infty} \frac{e^x}{e^{2x} + 1} \, dx$
		2. $\int_{e^5}^{\infty} \frac{1}{x(ln(x))^2} \, dx$
		3. $\int_{0}^{2} \frac{1}{(x-1)^2} \, dx$
		4. $\int_{0}^{\infty} \frac{e^{2x}}{e^{2x} + 1} \, dx$
		5. $\int_{0}^{9} \frac{1}{x-1} \, dx$
		6. $\int_{0}^{9} \frac{1}{\sqrt[3]{x - 1}} \, dx$
		7. $\int_{-\infty}^{\infty} x \, dx$
		8. $\int_{0}^{\infty} x e^{-x} \, dx$
		9. $\int_{-\infty}^{0} x e^{-x^2} \, dx$
		10. $\int_{e}^{\infty} \frac{1}{x \ln x} \, dx$
5. sequence and series
	1. compute the following telescopic series
		1. $\sum_{n = 1}^{\infty} \frac{3}{n^2 + 5n + 6}$
		2. $\sum_{n = 1}^{\infty} \frac{2}{n^2 + 2n}$


