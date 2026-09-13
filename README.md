# Camera Optics Lab

A computational imaging project exploring how diffraction, defocus, and optical aberrations affect image formation.

## Goal

Build a simple optical imaging model in Python and study how an ideal point source becomes a point spread function (PSF), and how that PSF changes real images.

## Questions

- Why does a point source not remain a perfect point after passing through an optical system?
- How do diffraction and defocus change the PSF?
- How do aberrations degrade image quality?
- Which optical effects matter most for the final image?

## Planned Steps

1. Simulate an ideal diffraction-limited PSF
2. Apply the PSF to a real image using convolution
3. Add defocus
4. Add optical aberrations
5. Compare image degradation quantitatively
6. Explore basic image recovery

## Current Progress

### 01 — Ideal Diffraction-Limited PSF

- Built a circular aperture model
- Computed the diffraction-limited PSF using a 2D Fourier transform
- Visualized the PSF in linear and logarithmic scale
- Applied the PSF to a real grayscale image using convolution
- Compared image blur for different aperture sizes
- Observed that a smaller aperture produces a broader PSF and stronger diffraction blur

## Example Result

![Aperture blur comparison](aperture_blur_comparison.png)

## Tools

- Python
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

## Status

Work in progress.
