# AIM:
To implement ASK  using MATLAB.

# SOFTWARE REQUIRED:
MATLAB

 
# PROGRAM:

clc;

t=0:0.0001:0.15;

m = square(2pi20*t);

c = sin(2pi80*t);

y1=(m.*c);

for i = 1:1500

if(m(i)==1)

    y1(i)=c(i);
    
else

    y1(i)=0;
    
end
end

figure(1)

subplot(3,1,1);

plot(m);

subplot(3,1,2);

plot(c);

subplot(3,1,3);

plot(y1);

# OUTPUT:
<img width="765" height="515" alt="image" src="https://github.com/user-attachments/assets/a280c652-d379-4c71-8f07-55b44684b70a" />



# RESULT:
Thus, generation of ASK was implemented using MATLAB.

 
