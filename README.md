# programacion_5.10 
%numeral 5.10
clf
clear all
z=0:2*pi;
x=cos(2*z);
v=cos(z)-sin(z);
plot(z,x,'--r');
hold on
plot(z,v,'b')
title('numeral5.10')
axis('auto')
