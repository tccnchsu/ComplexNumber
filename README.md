# ComplexNumber
Complex Number


MATLAB Lesson 10 - Plotting complex numbers
https://www.maths.unsw.edu.au/sites/default/files/MatlabSelfPaced/lesson10/MatlabLesson10_Complex.html

Line Plot Complex Numbers
https://www.mathworks.com/matlabcentral/answers/323493-line-plot-complex-numbers

z1 = 0 + 2j;
z2 = -1 + 1j;
z3 = -3 - 4j;
z4 = 0 - 1j;
z = [z1 ; z2; z3; z4] ;
plot(real(z),imag(z))   % line plot 
hold on
plot(real(z),imag(z),'*r') % marker plot
