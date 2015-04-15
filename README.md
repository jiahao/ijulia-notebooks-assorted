# Assorted IJulia notebooks

Assorted IJulia notebooks in various stages of usefulness for public consumption.

See https://github.com/jiahao/ijulia-notebooks for more polished notebooks.

- **BlockSVD**:
  Steps through the new blocked algorithm in
  [LAWN 283](http://www.netlib.org/lapack/lawnspdf/lawn283.pdf)
  for computing the singular value decomposition.

- **ECG model**:
  Implements a model for simulating human electrocardiogram (ECG) signals by
  McSharry, Clifford, Tarassenko, and Smith (2003)
  ([doi:10.1109/TBME.2003.808805](http://dx.doi.org/10.1109/TBME.2003.808805))
  and compares the model with some real patient data from the
  [MIMIC II database](https://mimic.physionet.org/database.html)

- **Hinton diagrams**:
  A simple code for generating Hinton diagrams using Compose.jl.

- **Nuclear energy levels**:
  Models experimental energy levels of atomic nuclei using random matrix theory.

- **Randomized SVD**:
  ~~Experimental implementations of randomized algorithms for the singular value
  decomposition and assorted related linear algebra functions.~~ Now mostly
  implemented in
  [IterativeSolvers.jl#33](https://github.com/JuliaLang/IterativeSolvers.jl/issues/33)

- **SVD of signals**:
  Looks at what the singular value decomposition can tell us about analyzing multiple time series.
