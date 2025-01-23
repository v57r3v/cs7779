java c
ECE MATLAB 4 Assignment
In this assignment, we will examine the design of digital IIR filters via the bilinear trans-form. and impulse invariance techniques. Suppose we wish to design a digital filter with the following specifications: passband from 0 to 0.4π, stopband from 0.5π to π. The passband ripple should not exceed 3 dB, and the stopband attenuation should always be at least 30 dB. Assume a sampling rate of 16 kHz (i.e., T = 1/16000) for this assignment. For the analog filters, please use the plotting range 0 : π/20 : π/T. For the digital filters, please use the plotting range 0 : π/200 : π.
1. To start with, we’ll need an analog filter. Determine the specifications on the analog filter that correspond to the digital specifications given above. Use the function ellip to design the filter. You can use ellipord to determine the correct order and cut-off frequency to give to ellip. Plot the frequency response using freqs, and confirm that it meets the specifications you worked out. Plot the polezero diagram for the filter. Since this is an analog filter, don’t use zplane. Instead, use roots to find the poles and zeros and plot them using plot.
2. Use the bilinear function to transform. your analog filter to a digital IIR filter. For this part, do not use any frequency pre-warping. Plot the frequency response and polezero diagram of the filter.代 写ECE MATLAB 4 AssignmentMatlab
代做程序编程语言 Also, zoom in on the passband and stopband and determine if they meet the spec. If not, explain why. We know that the bilinear transform. should map any roots of the analog filter in the left-half s-plane into the interior of the unit circle in the z-plane. Did this occur?
3. Repeat part 2), but this time use frequency pre-warping to ensure perfect accuracy at the passband edge frequency. How does the frequency response differ from the previous case? Does this filter meet the spec? How do the locations of the poles and zeros compare to part 2)?
4. Use the impinvar function to design a digital IIR filter from the analog filter designed in part 1) via the impulse invariance method. Show the frequency response and pole-zero diagram. Explain the differences inpassband and stopband ripple as compared to the bilinear transform. cases. How do the locations of the poles and zeros compare to the bilinear transform. cases? Were zeros on the imaginary axis in the splane mapped to the unit circle in the z-plane?
5. Repeat steps 1) and 3) using a Butterworth and Chebyshev type 1 filter. You can use the functions buttord, cheb1ord and butter,cheby1 to design the analog filter. Do the resulting filters meet the spec?Also, compare the order of the filters you get to the order of the one in part 1).







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
