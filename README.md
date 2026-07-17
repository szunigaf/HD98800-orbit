# HD 98800 Orbital Solution

This repository continues the orbital analysis of HD 98800 initiated in ["The HD 98800 quadruple pre-main sequence system. Towards full orbital characterisation using long-baseline infrared interferometry", Zúñiga-Fernández et al. 2021](https://arxiv.org/abs/2109.02841), and recently expanded with ["Peering through the disc of HD 98800 BaBb. Precise timing predictions for the HD 98800 AaAb occultation", Zúñiga-Fernández et al. 2026](https://arxiv.org/abs/2607.11599).

## Purpose

This is a public repository maintained to provide the community with updated and refined orbital solutions for the HD 98800 quadruple system. We regularly incorporate new observations and improve the orbital characterization of this complex hierarchical system.

## Repository Structure

- **AB**: Orbital analysis and disc occulation predictions for the outer binary pair
- **AaAb**: Orbital fit analysis for the inner AaAb binary
- **BaBb**: Orbital fit analysis for the inner BaBb binary
- **CSV folder**: Posterior distributions and orbital parameters for each subsystem
- **Plots folder**: Generated figures and visualizations

## Data and Methodology

We modelled our dataset with the [exoplanet](https://github.com/exoplanet-dev/exoplanet) software package, which extends the PyMC3 framework to support many of the custom functions and distributions required when fitting orbital parameters. Each subsystem folder contains:
- Astrometric measurements (`.csv` files)
- Radial velocity data from multiple instruments (HARPS, NIRPS, FEROS, etc. `.csv` files)
- Jupyter notebooks with the complete orbital fitting analysis
- Posterior distributions and orbital solutions

## Citation

If you use this data or analysis, please cite:
Zuñiga-Fernández et al. 2021 and 2026

## License

See [LICENSE](LICENSE) file for details.
