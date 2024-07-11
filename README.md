# lcs_codes

Data related to the research paper *Lift-Connected Surface Codes* [arXiv:2401.02911](https://doi.org/10.48550/arXiv.2401.02911/), [Quantum Science and Technology: 10.1088/2058-9565/ad5eb6](https://iopscience.iop.org/article/10.1088/2058-9565/ad5eb6)

## Files:
- `data.csv` contains raw data obtained from numerical simulations for code capacity and phenomenological noise
- `data_cicuit_level.csv` contains raw data obtained from numerical simulations for circuit level noise
- `./circuits/` contains [stim circuits](https://github.com/quantumlib/Stim/blob/main/doc/file_format_stim_circuit.md) for LCS codes
  - `{l}_{L}_{n_cycles}.stim`
- `parity_check_matrices/{l}_{L}/` containes matrices for $(l,L)$-LCS code in [alist format](http://www.inference.org.uk/mackay/codes/alist.html)
  - `{l}_{L}_hx.alist` (pcm of X-Stabilizers)
  - `{l}_{L}_hz.alist` (pcm of Z-Stabilizers)
  - `{l}_{L}_lx.alist` (X-logical operators)
  - `{l}_{L}_lz.alist` (Z-logical operators)
