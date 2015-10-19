# Punto.-Q.5.37
Further Analysis
Q.5.37 Load and run the program of Example 5.6.
>> Beta = linspace(0,2*pi,50);

>> R1=10*sin(Beta);

>> subplot(2,2,1)

>> polar(Beta,R1)

>> title(‘10sin(Beta)’)

>> subplot(2,2,2)

>> R2 = -R1;

>> polar(Beta,R2)

>> title(‘-10sin(Beta)’)

>> subplot(2,2,3)

>> R3 =10*cos(Beta);

>> polar (Beta,R3)

>> title(‘10cos(Beta)’)

>> subplot(2,2,4)

>> R4 = -R3;

>> polar(Beta,R4)

>> title(‘-10cos(Beta)’)
