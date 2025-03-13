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
	2. $\int \tan^m{x} \sec^n{x} \, dx$
		- case: $n > 0$ even $\rightarrow$ use $u = \tan x$ substitution
		- case: $n > 0$ odd & $m$ odd (or $n$ even & $m$ odd) $\rightarrow$ use $u = \sec{x}$ substitution
1. trigonometric substitution
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
			- 