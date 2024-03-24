# ComputerSystemSecurity
This repository contains three Jupyter Notebook files:

## [LAB5-Diffie-Hellman.ipynb](./LAB5-Diffie-Hellman%20.ipynb)
- Implements the Diffie-Hellman key exchange algorithm, including functions for generating public and secret keys, and checking for primitive roots.
## [Lab3-Caesar cipher.ipynb](./Lab3-Caesar%20cipher.ipynb)
- Implements a custom encryption algorithm based on the Caesar cipher, allowing encryption and decryption of text messages with user-defined shift values.
## [Lab4-Hill cipher.ipynb](./Lab4-%20Hill%20cipher.ipynb)


- Implements the Hill cipher encryption and decryption algorithm, including functions for matrix manipulation and key validation.

<br/> 

# LAB5-Diffie-Hellman

This Jupyter Notebook contains Python code for implementing the Diffie-Hellman key exchange algorithm. 

## Introduction

The Diffie-Hellman key exchange is a method for securely exchanging cryptographic keys over a public channel. It allows two parties to agree on a shared secret key without having to directly communicate the key. This notebook provides functions to generate public and secret keys, as well as to check if a given number is a primitive root modulo a prime number.

## Contents

- `dh_generatePublicKey`: Function to generate a public key using the Diffie-Hellman algorithm.
- `dh_generateSecretKey`: Function to generate a secret key using the Diffie-Hellman algorithm.
- `primitive_root_check`: Function to check if a given number is a primitive root modulo a prime number.
- Main program: Allows users to input prime numbers `P` and `G`, along with private numbers `a` and `b`, to generate shared secret keys.

## Usage

To use this notebook, simply execute the cells in order. The main program will prompt you to input prime numbers `P` and `G`, along with private numbers `a` and `b`. It will then generate shared secret keys for Alice and Bob.

## Requirements

- Python 3.x
- Jupyter Notebook
- sympy library

<br/> 
<br/> 


# Lab3-Caesar Cipher

This Jupyter Notebook contains Python code for implementing the Caesar cipher encryption algorithm.

## Introduction

The Caesar cipher is one of the simplest and most widely known encryption techniques. It is a type of substitution cipher in which each letter in the plaintext is shifted a certain number of places down or up the alphabet. In this notebook, we provide a custom implementation of the Caesar cipher encryption algorithm.

## Contents

- `customEncrypt`: Function to encrypt text using the Caesar cipher algorithm.
- `testCustomEncrypt`: Function to test the custom encryption algorithm by encrypting and decrypting user-provided input.

## Usage

To use this notebook, simply execute the cells in order. The `testCustomEncrypt` function will prompt you to enter a UserID and password as text, along with values for `n` (shift) and `d` (direction). It will then encrypt and decrypt the input text using the Caesar cipher algorithm and display the results.

## Requirements

- Python 3.x
- Jupyter Notebook

<br/> 
<br/> 


# Lab4 - Hill Cipher

This Jupyter Notebook contains Python code for implementing the Hill cipher encryption and decryption algorithm.

## Introduction

The Hill cipher is a polygraphic substitution cipher based on linear algebra, where each letter is represented by a number and arranged in a matrix. Encryption and decryption are performed using matrix multiplication. In this notebook, we provide functions to encrypt and decrypt text using the Hill cipher algorithm.

## Contents

- `cipher_encryption`: Function to encrypt plaintext using the Hill cipher algorithm.
- `cipher_decryption`: Function to decrypt ciphertext using the Hill cipher algorithm.
- Example: Demonstrates how to use the encryption and decryption functions with a sample plaintext and key.

## Usage

To use this notebook, simply execute the cells in order. The example cell at the end of the notebook demonstrates how to encrypt and decrypt a sample plaintext using the Hill cipher algorithm.

## Requirements

- Python 3.x
- Jupyter Notebook
- NumPy library
