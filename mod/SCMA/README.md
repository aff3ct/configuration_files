SCMA codebook input files for the AFF3CT SCMA modem.

**Format**:

1st line: number_of_users (*V*) number_of_orthogonal_resources (*K*) codebook_size (*M*) (3 numbers)

Re Im ... Re Im parts of codeword symbols on one orthogonal_resource (2*M* columns)

...

*KV* rows total

...

Re Im ... Re Im parts of codeword symbols on one orthogonal_resource (2*M* columns)

The codebooks sets (CS) **CS1**-**CS7** from paper [Vyacheslav P. Klimentyev, Alexander B. Sergienko "SCMA Codebooks Optimization Based on Genetic Algorithm"](https://ieeexplore.ieee.org/document/8011314/).

The **CS8** from paper [Vyacheslav P. Klimentyev, Alexander B. Sergienko "Detection of SCMA signal with channel estimation error"](https://ieeexplore.ieee.org/document/7561515/) (CS2 in the paper).
