Differential Cryptanalysis
======
This is a submission for UVic's Applied Cryptography Jan2021 course project. It implements differential cryptanalysis as described in [this document](https://www.engr.mun.ca/~howard/PAPERS/ldc_tutorial.pdf)

The code is capable of attacking the a simple encryption function implemented according to the toy cipher. It uses all the techniques given in the document and uses them to carry out the differential cryptanalysis attack.

The point of the attack is to retrieve the last set of keys used by the encryption function interactively.

## How to run
To run the code, install jupyter notebook by following the steps given [here](https://jupyter.org/install)

There are no requirements other than python3 and the python standard library
