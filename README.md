# Formal Verification of ECCs for Memories using ACL2

This repository provides two libraries for the verification of Error Correction Codes (ECCs) generally used in memories: *Standard_Functions* and *ECC_Library*. *Standard_Functions* contains some basic functions and their associated properties. *ECC_Library* contains Encoder/Decoder definitions and theorems for Hamming (7,4) codes and ½ rate Convolutional codes.

The files *MemModel-with-Hamming-Code* and *MemModel-with-Convolutional-Code* provides the compiled script for verifications of the aforementioned ECCs, and their implementation on a byte-addressable record based memory.

## Prerequisite

Before staring, make sure ACL2 theorem prover is installed and running on your system. Installation instructions can be found [here](http://www.cs.utexas.edu/users/moore/acl2/v8-0/HTML/installation/installation.html).

## Citing the Work

