# FFT Filters
Applies a simple low and high pass filters to an image using NumPy.

Written in a jupyter notebook, only requirements are:
- ipykernel
- pip
- numpy
- pillow
- matplotlib

Better results could be achieved by using a Gaussian filter.

# Output
Original image:

![](https://github.com/peterc-s/fft-filters/blob/main/pops_512.jpg?raw=true)

Original FFT:

![](https://github.com/peterc-s/fft-filters/blob/main/output/pops_fft.png?raw=true)

## Low Pass
### Circular
Filtered image:

![](https://github.com/peterc-s/fft-filters/blob/main/output/pops_low_pass.png?raw=true)

Filtered FFT:

![](https://github.com/peterc-s/fft-filters/blob/main/output/pops_low_pass_fft.png?raw=true)

### Gaussian
Filtered image:

![](https://github.com/peterc-s/fft-filters/blob/main/output/pops_low_pass_gauss.png?raw=true)

Filtered FFT:

![](https://github.com/peterc-s/fft-filters/blob/main/output/pops_low_pass_gauss_fft.png?raw=true)

## High Pass
### Circular
Filtered image:

![](https://github.com/peterc-s/fft-filters/blob/main/output/pops_high_pass.png?raw=true)

Filtered FFT:

![](https://github.com/peterc-s/fft-filters/blob/main/output/pops_high_pass_fft.png?raw=true)

### Gaussian
Filtered image:

![](https://github.com/peterc-s/fft-filters/blob/main/output/pops_high_pass_gauss.png?raw=true)

Filtered FFT:

![](https://github.com/peterc-s/fft-filters/blob/main/output/pops_high_pass_gauss_fft.png?raw=true)
