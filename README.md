# Measurement of the Raw Asymmetry in Λb⁰ → Λ⁰(→ pπ⁻) J/ψ(→ e⁺e⁻)

B.S. Physics thesis, University of Groningen (Van Swinderen Institute for Particle Physics and Gravity), October 2024.
Supervisors: Dr. Ann-Kathrin Perrevoort, Prof. Steven Hoekstra. Thesis grade: 9/10.

## Summary
This decay is a normalization channel for testing CP violation in Λb⁰ → e⁺e⁻Λ⁰, so it must show no CP violation itself. Using 5.57 fb⁻¹ of LHCb Run 2 data (2016–2018, √s = 13 TeV), I selected signal candidates, suppressed the B⁰ → J/ψ K⁰s background with a mass veto optimized on Monte Carlo simulation, and extracted particle and antiparticle yields with binned fits. The raw asymmetry for the combined dataset is **A_raw = 0.029 ± 0.032**, consistent with no CP violation.

## Method
- **Selection:** candidates reconstructed from a Λ⁰ and a J/ψ → e⁺e⁻.
- **Background veto:** Monte Carlo study of B⁰ → J/ψ K⁰s misidentification; veto window chosen to keep 85% of the signal while letting through 8% of the background.
- **Fits:** binned fits with a double-Gaussian signal and an exponential combinatorial background; initial parameters from fits to Monte Carlo.
- **Samples:** analysed separately by track type (LL = long tracks, DD = downstream tracks) and magnet polarity (MU = MagUp, MD = MagDown) to test for detection asymmetries, then combined.

## Contents
| File | Content |
|---|---|
| `Bachelor_Research_Project_Ludovica_De_Mare.pdf` | Full thesis |
| `LLMD`, `LLMU`, `DDMD`, `DDMU` `.ipynb` | Fits for each track type × polarity sample |
| `Monte_Carlo_*.ipynb` | Fits to simulated data for initial fit parameters |
| `Veto_DDMD.ipynb`, `Monte_carlo_cut_veto_DDMD.ipynb` | Background veto optimization |
| `Particle_and_antiparticle.ipynb`, `Monte_Carlo_Particle_and_antiparticle.ipynb` | Λb⁰ vs. anti-Λb⁰ yields and raw asymmetry |

## Tools
Python: uproot, NumPy, SciPy, Matplotlib.

*The data belong to the LHCb collaboration and are not included in this repository.*
