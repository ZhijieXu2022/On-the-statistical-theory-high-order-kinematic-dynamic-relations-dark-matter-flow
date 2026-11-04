# High order kinematic and dynamic relations for dark matter flow: manuscript and data

Manuscript and CSV data for **Xu, Z. (2024), *On the statistical theory of self-gravitating collisionless dark matter flow: High order kinematic and dynamic relations*, Physics of Fluids 36, 075146**, doi:[10.1063/5.0215026](https://doi.org/10.1063/5.0215026), arXiv:[2202.02991](https://arxiv.org/abs/2202.02991).

The same files are archived on Zenodo: [doi:10.5281/zenodo.23910393](https://doi.org/10.5281/zenodo.23910393).

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23910393.svg)](https://doi.org/10.5281/zenodo.23910393)

## Major findings

Virgo SCDM N-body simulation, redshifts z = 10 to 0.

- Kinematic relations of any order are derived for incompressible, constant-divergence and irrotational flow, and validated by the simulation.
- On large scales, third-order velocity correlations can be related to the density correlation or the pairwise velocity.
- The p-th order velocity correlations follow a^((p+2)/2) for odd p and a^(p/2) for even p (a = scale factor). The fitted exponents for odd p are smaller than these predictions.
- The overdensity is proportional to the density correlation on the same scale, <delta> ∝ <delta delta'>; the velocity dispersion on a scale r is proportional to the overdensity on that scale.
- The effective viscosity of the adhesion model originates from velocity fluctuations; the negative viscosity is due to the inverse energy cascade.
- On small scales, a self-closed velocity evolution is obtained by splitting velocity into motion within haloes and motion of haloes. Vorticity, enstrophy and energy evolution follow from it.
- The mean pairwise velocity follows <Δu_L> = −H a r. The third moment follows <(Δu_L)^3> ∝ ε_u a r, with a constant energy-cascade rate ε_u ≈ −4.6×10⁻⁷ m²/s³.
- The combined kinematic and dynamic relations give exponential velocity correlations on large scales and one-fourth power-law correlations on small scales; the p-th order correlations follow a^((3p−5)/4) for odd p and a^(3p/4) for even p.

## Major findings

Virgo SCDM N-body simulation, redshifts z = 10 to 0:

- Kinematic relations of any order are derived for incompressible, constant-divergence and irrotational flow, and validated by the simulation.
- On large scales, third-order velocity correlations can be related to the density correlation or the pairwise velocity.
- The p-th order velocity correlations follow a^((p+2)/2) for odd p and a^(p/2) for even p (a = scale factor). The fitted exponents for odd p are smaller than these predictions.
- The overdensity is proportional to the density correlation on the same scale, ⟨δ⟩ ∝ ⟨δδ'⟩; the velocity dispersion on a scale r is proportional to the overdensity on that scale.
- The effective viscosity of the adhesion model originates from velocity fluctuations; the negative viscosity is due to the inverse energy cascade.
- On small scales, a self-closed velocity evolution is obtained by splitting velocity into motion within haloes and motion of haloes. Vorticity, enstrophy and energy evolution follow from it.
- The mean pairwise velocity follows ⟨Δu<sub>L</sub>⟩ = −H a r. The third moment follows ⟨(Δu<sub>L</sub>)<sup>3</sup>⟩ ∝ ε<sub>u</sub> a r, with a constant energy-cascade rate ε<sub>u</sub> ≈ −4.6×10⁻⁷ m²/s³.
- The combined kinematic and dynamic relations give exponential velocity correlations on large scales and one-fourth power-law correlations on small scales; the p-th order correlations follow a^((3p−5)/4) for odd p and a^(3p/4) for even p.

## Contents

| Path | Content |
|---|---|
| `P19_revised.pdf` | Manuscript, revised edition (28 pages) |
| `statistics/` | 104 files: every pair statistic as a function of separation r, at redshifts z = 10 ... 0 (level-2 pair statistics, level-3 statistics with the Riemann and trapezoidal integration rules, and the other intermediate quantities) |
| `tables/` | 9 files: u(z), fitted coefficients, scaling exponents, the vorticity-equation terms on CIC grids, the matter power spectrum (N-body and theory), numbers quoted in the text, the equation audit, and the comparison with the published figure arrays |
| `figures/` | 20 files: every plotted series of the revised figures |
| `figures_published_rule/` | 20 files: the same series built with the original post-processing of the author |
| `CITATION.cff`, `LICENSE` | citation metadata and licence |

## Format of the CSV files

Each file starts with comment lines beginning with `#`, then a header row, then data.

- `# Publisher`: author and contact.
- `# Updated`: date of the last update.
- `#Name`: what the file contains.
- `#Ref. [n]`: the equation and figure of the paper the data belong to, with the DOI.
- `#Note`: processing notes, where needed.

Statistics files use a common layout: the first column is the separation r in Mpc/h, and each further column is one redshift (`z=10`, `z=5`, ... `z=0.0`). Values of -1 mark separations where the statistic is not defined for that redshift. Velocities are in units of u0 (the rms velocity at z = 0) unless the header says otherwise. Distances are comoving, in Mpc/h.

## Related datasets

- Dark matter flow dataset, Part I (halo-based statistics): doi:[10.5281/zenodo.6541231](https://doi.org/10.5281/zenodo.6541231)
- Dark matter flow dataset, Part II (correlation-based statistics): doi:[10.5281/zenodo.6757654](https://doi.org/10.5281/zenodo.6757654)
- Dark matter flow dataset (all files): doi:[10.5281/zenodo.6586213](https://doi.org/10.5281/zenodo.6586213)
- Earlier paper (second-order statistics): doi:[10.1063/5.0151129](https://doi.org/10.1063/5.0151129)
- 2022 preprint record of this work: doi:[10.5281/zenodo.6640684](https://doi.org/10.5281/zenodo.6640684)

The simulation is the Virgo Consortium SCDM run (Jenkins et al. 1998; Frenk et al. 2000).

## Citation

Please cite the article (doi:[10.1063/5.0215026](https://doi.org/10.1063/5.0215026)) and the data archive (doi:[10.5281/zenodo.23910393](https://doi.org/10.5281/zenodo.23910393)). GitHub's "Cite this repository" button uses `CITATION.cff`.

## Licence

The text, figures and data in this repository are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). See `LICENSE`.
