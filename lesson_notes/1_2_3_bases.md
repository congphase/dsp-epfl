# Intro

A basis is a vector space's "skeleton", so to speak. It gives the space structure and allows us to decompose any element in the space into a linear combination of simple building blocks, namely, the basis vectors. Bases are extremely important in signal processing: we will see in the next module that the Fourier Transform is simply a change of basis. 

# Content
![](../docs/bases_intro.png)

- Notice the $\{w^{(k)}\}$ notation to indicate the set of the (base) vectors

Examples:

![](../docs/canonical_R2_basis.png)

![](../docs/another_canonical_R2_basis.png)

![](../docs/not_linearly_independent_vectors.png)

- $g^{0}$ and $g^{1}$ are not linearly independent (so they're linearly dependent?). As a result, we cannot describe any vector with this pair of vectors


"Can we describe an infinite length signal?". Yes.

![](../docs/a_basis_for_l2_Z_.png)

Basis for function vector spaces

![](../docs/develop_basis_for_function.png)

- One of the most famous is the Fourier basis

    ![](../docs/fourier_basis.png)

    - interval $[-1,1]$
    - basis vector 0, 1, 2, ...

    - Take a look at an example

    ![](../docs/rewrite_a_signal_with_fourier.png)

    - Notice how $\sin{\pi t}$ corresponses to 2 (in the image above) and accordingly expressed in the handwritten equation

    ![](../docs/n_2.png) ![](../docs/n_10.png)

    - The more we add, the more we approximate to the function that we want to approximate