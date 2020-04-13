# CMPE242_FFT_Assignment-

## Aim
1. To calculate DFT using fft.c program from the class GitHub. Use 1024 pts from half-period of a cosine wave. 
2. To verify hand calculation in class, ADC Output (2,3,4,4).
3. Power Spectrum Calculation
4. Plot the power spectrum

## Solution

### Question 1
1. Construct the cos signal of 1024 pts by using a for loop from 0 to 1023 and the function x=cos(2*pi*x)
2. Take M = 10 and N = 2^10
3. Run fft function
4. Store all the values in a text file and plot in Excel

### Question 2
1. Take input signal as {0.0, 2.0, 3.0, 4.0, 4.0}
2. Take M = 2 and N = 2^2
3. Run fft function
4. Store all the values in a text file and plot in Excel
5. Calculate power spectrum values using the formula sqrt(pow(X[j].a,2)+pow(X[j].b,2));
6. Store all the values in a text file and plot in Excel
