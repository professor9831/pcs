# pcs
f=0.2;  t=0:0.1:10;   x=cos(2*%pi*t*f);  plot(t,x) title('cosine wave');

f=0.2;   t=0:0.1:10;   x=cos(2*%pi*t*f);  plot2d3(t,x) title('cosine wave');

 clf;
t=linspace(0,10,500);
 vm=5*squarewave(t);
 plot(t,vm)
 
 clf;
t=linspace(0,10,500);
 vm=5*squarewave(t);
 plot2d3(t,vm)
 
  t=-10:0.1:10;
 x=sinc(t);
plot(t,x)

 t=-10:0.2:10;
x=sinc(t);
 plot2d3(t,x)

 
