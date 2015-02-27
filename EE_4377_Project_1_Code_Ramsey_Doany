% EE4377 Project 1
% MATLAB code for EE_4377_Project_1_Doany_Ramsey
% Ramsey Doany
% 2/27/2015

clc      % Clear screen 
clear    % Clear all variables
A = 3; f= 1000; omega = 2*pi*f; 
angle = degtorad(33); T=1/f;
t=linspace(-3*T,3*T,1000);
x_t=3*cos(omega*t+angle);
subplot(4,2,2)
plot(t,x_t, 'linewidth',2);grid on
subplot(2,3,1)
u_t=heaviside(t);
plot(t,u_t, 'linewidth',2);grid on
subplot(4,2,3)
plot(t,x_t.*u_t, 'linewidth',2);grid on
f(t)=cos(omega*t)*sin(omega*t)*u(t-1)
