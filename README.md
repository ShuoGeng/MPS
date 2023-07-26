# Basic Tensor Calculations
This repository will show some basic tensor calculations
1. In file Givens_Householder_transformation.py, it will randomly generate two nonzero vectors $\xi$ and $\eta$ in $\mathbb{C}^{n}$, with $\lVert x \rVert_2$. where the dimensions of two vectors will be given by users. It will show the matrix generated by way of Givens transformation and Householder transformation. Then it will verify the matrix $U$ transforms the $\xi$ vectors into the $\eta$ vectors. Finally, it will verify $UU^{\dagger}= I_n$. The program will be looped 3 times, meaning the user must give the dimension parameter 3 times.
2. In the file ground_energy.py, it will calculate the ground state energy $E_0$ and the first excited state energy $E_1$ for spin-1/2 antiferromagnetic Heisenberg chains of lengths L = 4, 6, 8, 10, 12, respectively. And then it will calculate the energy gap. Finally, U(1) symmetry will be used to simplify the calculation
3. In the file specific_heat, it will calculate the specific heat (Cv) of the spin-1/2 antiferromagnetic Heisenberg chain with length L=8.# The partition function Z is given by: $Z = tr(e^{-\beta H})$, where $\beta = 1/T$ is the inverse temperature and H is the Hamiltonian.The specific heat $C_v = 1/L*<H>/dT$, and $ <H> = tr(H e^{-\beta *H})/Z $
4. In the file svd.py, it gives a realization about SVD(Singular Value Decomposition). SVD is an important procedure in various fields. I try to make it and avoid importing some modules directly.
5. Others: like MPS, DMRG algorithm, continuing... \avg{x}
