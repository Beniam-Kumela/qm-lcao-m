# Series of Quantum Finite Potential Wells as an Energy State Approximation of Solids
This repository contains a Mathematica implementation of numerical methods involved in the linear combination of atomic orbitals method as described in the following [paper](https://drive.google.com/file/d/1o0BvK3saxIsB-6zXXD2Z6mZ4xm62ZN3k/view?usp=sharing).

Potential well:

![image](https://github.com/user-attachments/assets/33e2917e-d287-456f-8d0e-62aa39dfa123)

Corresponding energy states:

![image](https://github.com/user-attachments/assets/17bb4960-332e-4930-8bbe-87db6c31ae5c)

## Usage
Please follow the steps in order to use and make changes to the code:

### 1.  Install Mathematica
To install, follow these [instructions](https://reference.wolfram.com/language/tutorial/InstallingMathematica.html.en).
### 2. Download documents
To download, press the green "Code" button, download, and extract the zip.
### 3. Run Code
To run code, navigate to the file "qm_multi-finite_wells_code.pdf". Copy the contents of the file into a new Mathematica notebook exactly, then run.

## Future
I would like to improve the generalizability of periodic potential behavior by using Bloch's theorem. I would also like to use a more realistic, Morse-like potential. Lastly, I would like to use computationally efficient PDE solvers like the Thomas algorithm for sparse, tridiagonal matrices.
