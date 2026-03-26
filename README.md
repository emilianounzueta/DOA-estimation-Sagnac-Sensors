Acoustic DOA Estimation using CCV and MUSIC

This repository presents a complete and reproducible pipeline for
Direction of Arrival (DOA) estimation using acoustic signals acquired
from a fiber optic sensing system based on a Sagnac interferometer.

The project translates and extends MATLAB-based signal processing
algorithms into Python, integrating tools commonly used in Data Science
and Scientific Computing.

![Texto alternativo de la imagen](figures/1.sagnac_sensor_system.png)
*Figura 1: Descripción de la gráfica de dispersión de los datos.*
------------------------------------------------------------------------

Project Overview

The goal of this project is to estimate the angle of arrival of an
acoustic source using experimental data and advanced signal processing
techniques.

Two main methods are implemented and compared:

-   CCV (Cross-Correlation Vector)
-   MUSIC (Multiple Signal Classification)

------------------------------------------------------------------------

Methodology

CCV Method

-   FFT-based cross-correlation
-   Time-delay estimation
-   Angle reconstruction

MUSIC Algorithm

-   Covariance matrix estimation
-   Eigen decomposition
-   Noise subspace projection
-   Spectral peak detection

------------------------------------------------------------------------

Notebooks

01_signal_loading_and_fft.ipynb

-   Load MATLAB data
-   Signal visualization
-   FFT analysis

02_doa_estimation_ccv_music.ipynb

-   Implementation of CCV and MUSIC
-   DOA estimation
-   Statistical analysis
-   Visualization with error bars

------------------------------------------------------------------------

Dataset

-   1024 samples
-   13 positions
-   10 measurements
-   Distances: 0.2m, 0.3m, 0.4m, 0.5m

Structure: [samples, position, measurement]

------------------------------------------------------------------------

Installation

git clone https://github.com/emilianounzueta/acoustic-doa-estimation.git

pip install -r requirements.txt

------------------------------------------------------------------------

Requirements

numpy scipy matplotlib jupyter

------------------------------------------------------------------------

Article

https://doi.org/10.1080/01468030.2025.2485871

------------------------------------------------------------------------

Author

Emiliano-Ehecatl García-Unzueta

------------------------------------------------------------------------

License

