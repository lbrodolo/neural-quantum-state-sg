# neural-quantum-state-sg [DATASET LINK] (https://zenodo.org/records/11534964)
## Dataset form "Zero-temperature Monte Carlo simulations of two-dimensional quantum spin glasses guided by neural network states" [10.1103/PhysRevE.110.065305]

### 2D QUANTUM EDWARDS-ANDERSON  GROUND-STATE DATASET:
The dataset contains coupling and energy data for 50 instances of a 2D quantum Edwards-Anderson model at Gamma (transverse field) = 1.8, featuring N=LxL=100 spins on a square lattice of side-length L=10 with periodic boundary conditions. The couplings are sampled from a Gaussian distribution with zero mean and unit variance.
The dataset consists of two text files containing coupling values and the corresponding ground-state energies.

### Coupling Data (`coup_dataset.txt`)
The file `coup_dataset.txt` contains fifty sets of coupling data. Each set consists of three columns representing the indices `i`, `j`, and the coupling value `J_ij`, respectively.
The spin indices range from 1 to 100, ordered progressively by rows. Each set of coupling data is separated by two empty lines.

### Energy Data (eng_dataset.txt)
The file `eng_dataset.txt` contains fifty rows of energy data corresponding to the coupling sets in `coup_dataset.txt`. Each row contains two columns representing the energy value and its associated statistical error-bar, rounded to the fifth decimal digit.
