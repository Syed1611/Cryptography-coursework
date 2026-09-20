# Cryptography Coursework

Python notebooks developed during my MS in Computer Science at Oklahoma City University to explore cryptographic algorithms, mathematical operations, and protocol behavior.

## Contents

| Notebook                                                     | Topics                                                                                               |
| ------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------- |
| Vigenere Cipher and Kasiski Examination                      | Encryption, decryption, repeated-sequence analysis, and key-length estimation                        |
| DES Round 1 Encryption Trace                                 | Initial permutation, subkey generation, expansion, S-box substitution, and the first Feistel round   |
| AES Transformations - SubBytes ShiftRows and AddRoundKey     | Selected AES operations on a state matrix                                                            |
| Diffie-Hellman Key Exchange and MITM Simulation              | Shared-secret calculation and a numerical demonstration of unauthenticated key exchange interception |
| RSA Decryption and Message Authentication with HMAC and CMAC | RSA decryption, HMAC-SHA256, and AES-CMAC                                                            |

## Tools

* Python
* Jupyter Notebook / Google Colab
* Python standard libraries, including math, hashlib, and hmac
* The cryptography package for AES-CMAC

## Running the Notebooks

1. Download or clone the repository.
2. Open a notebook in Jupyter Notebook or Google Colab.
3. Install any required dependencies. The CMAC exercise requires the `cryptography` package.
4. Run the cells in order.

The exercises use sample inputs defined within the notebooks.

## Learning Context

These notebooks document coursework and educational demonstrations. Some implement selected algorithm steps rather than complete encryption systems. The small numerical examples and demonstration keys are intended for learning, not for protecting real data.

## Author

**Syed Haseeb Ali**
MS in Computer Science, Oklahoma City University
