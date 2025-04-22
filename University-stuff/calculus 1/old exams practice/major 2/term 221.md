differentiate the following function:
$$y=\frac{2x^3}{\sqrt{ x-1 }}$$
we have to use the quotient rule which states that
$$\left( \frac{f}{g} \right)^1=\frac{f^1g-fg^1}{g^2 }$$
so the derivative will become:
$$y^1=\frac{(6x^2)(\sqrt{ x-1 })-(2x^3)\left( \frac{1}{2\sqrt{ x }} \right)}{\sqrt{ x-1 }^2}$$
now differentiate this equation:
$$y=(x+3\sqrt{ x })e^x$$
we use the product rule which states that:
$$f\times g=f^1g+fg^1$$
by using the product rule we can solve the equation
$$y^1=\left(  1+\frac{3}{2\sqrt{ x }} \right)(e^x)+(x+3\sqrt{ x })(e^x)$$
#Q3. now differentiate this question
$$y=(x+1)^{\sin x}$$
we apply ln to both sides to bring the upper function down:
$$\ln y=\sin x\ln(x+1)$$
now we differentiate both sides and use the product rule on the right hand side:
$$\frac{y^1}{y}=(\cos x)(\ln (x+1))+(\sin x)\left( \frac{1}{(x+1)} \right)$$
now we multiply both sides with y to get y prime:
$$y^1=((\cos x)(\ln (x+1))+(\sin x)\left( \frac{1}{(x+1)} \right))(x+1)^{\sin x}$$
#q4. now solve this question:
$$y=e^{x^3+4x}+\cos(2x^2+5x)$$
we can use the chain rule which states that:
$$(e^u)^1=e^uu^1$$
by applying this rule we can solve the question:
$$
y^1=e^{x^3+4x}(3x^2+4)-\sin(2x^2+5x)(4x+5)
$$
#q5. now solve this question:
$$
y=\ln(7x^3+2x^2+5)
$$
we differentiate the function:
$$
y^1=\frac{21x^2+4x}{(7x^3+2x^2+5)}
$$
#q6. now find the equation of the tangent line to the curve:
$$y=2xe^x$$
at the point (0,0).
you have to memorize the rule of the tangent line to solve this question. the rule is:
$$
y-f(a)=f^1(a)(x-a)
$$
now substitute the values into the rule:
$$
y-f(0)=f^1(0)(x-0)
$$
we just simplify:
$$
y=f^1(0)x
$$
we have to find f prime:
$$
f^1(x)=2e^x+2xe^x
$$
now find f prime of (0):
$$
f^1(0)=2e^0+2(0)e^0=2
$$
so now we substitute into the formal equation we had:
$$y=2x$$
and that's the final answer.
#q7. find the derivative of this equation:
$$
y\sin(2x)=x\cos(2y)
$$
we use implicit differentiation to find y prime:
$$
y^1\sin(2x)+y\cos(2x)2=\cos(2y)+x(-\sin(2y)2y^1)
$$
now we move y prime into the left hand side and move the rest into the right hand side:
$$
y^1\sin(2x)+x\sin(2y)2y^1=\cos(2y)-y\cos(2x)2
$$
now we take y prime as a common factor:
$$
y^1(\sin(2x)+2\sin(2y))=\cos(2y)-2y\cos(2x)
$$
now we get rid of the stuff next to y prime:
$$
y^1=\left( \frac{\cos(2y)-2y\cos(2x)}{\sin(2x)+2\sin(2y)} \right)
$$
#q8. find the horizontal asymptote of the curve:
$$
f(x)=\frac{2x^2+x-1}{x^2+x-2}
$$
to find the horizontal asymptote we need to find the limit as x approaches negative and positive infinity:
$$
\lim_{ x \to \pm\infty } \frac{2x^2+x-1}{x^2+x-2} 
$$
we now take the highest power of both sides:
$$
\lim_{ x \to \pm\infty } \frac{2x^2}{x^2} 
$$
we delete x^2 from both sides:
$$
\lim_{ x \to \pm\infty } 2=2 
$$
which means that the Horizontal Asymptote is y=2