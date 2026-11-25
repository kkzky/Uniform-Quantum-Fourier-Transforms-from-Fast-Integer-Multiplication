# Uniform Quantum Fourier Transforms from Fast Integer Multiplication

Zhou Kangyun

The paper constructs a polynomial-time uniform family of unitary circuits that approximate the quantum Fourier transform on $q$ qubits. For fixed or inverse-polynomial error and any fixed $\delta>0$, the circuits use $O_\delta(q(\log\log q)^{1/2+\delta})$ elementary Clifford and $T$ gates in total, including the cost of preparing and uncomputing auxiliary registers. The construction implements OpenAI's integer multiplication algorithm as a Boolean circuit and reuses one phase-gradient register throughout the QFT recursion of Kayal and coauthors.

The paper also gives a deterministic algorithm that computes the rotation angle in Kayal and coauthors' exact circuit to $d$ bits of precision in time polynomial in $q$ and $d$. With intermediate measurements and unit-cost exact dyadic phase gates, a separate construction implements the exact QFT in $O(M(q)+q)$ gates and measurements on every branch, where $M(q)$ is the Boolean circuit size for multiplying two $q$-bit integers.

[Read the paper (PDF)](./Uniform%20Quantum%20Fourier%20Transforms%20from%20fast%20integer%20multiplication.pdf) · [LaTeX source](./uniform_quantum_fourier_transforms_from_fast_integer_multiplication.tex)
