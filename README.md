# Neural Network Based Key Exchange Using Tree Parity Machine

This repository contains the implementation and simulation of a neural-network-based key exchange protocol using a **Tree Parity Machine (TPM)**, 
developed as part of my MSc dissertation in **Advanced Computer Science at the University of Liverpool**.

## Overview

The project explores **post-quantum candidate approaches** for secure key exchange between two parties. 
Traditional cryptographic methods such as RSA and Diffie–Hellman rely on number-theoretic assumptions that may be vulnerable to large-scale quantum computers in the future.

This work investigates an alternative approach where two parties synchronize their secret keys using a Tree Parity Machine through mutual learning over a public channel.

## What this project includes

- A Python implementation of the **Tree Parity Machine (TPM)**  
- Synchronization simulation between two TPM instances  
- Experiments with different protocol variants  
- Analysis of attack strategies  
- Evaluation of protocol resilience and recommendations for improvement  

## Key Features

- Object-oriented implementation using a dedicated `TreeParityMachine` class  
- Support for both discrete and continuous weight representations  
- Weight synchronization mechanism  
- Manhattan distance metric for comparing TPM states  
- Randomized weight initialization strategy  

## Technologies Used

- Python  
- NumPy  
- Pandas  
- Matplotlib  

## How to Run

Clone the repository:
git clone https://github.com/imranmurtaza110/key_exchange_using_neural_networks.git


Navigate to the project folder and run the main simulation script.

## Disclaimer

This protocol is an emerging research direction. While it shows promise, it is **not yet proven secure** against all classical and quantum attacks and requires further investigation before any real-world deployment.

## Author

Syed Imran Murtaza Zaidi
Software Engineer
MSc Advanced Computer Science  
website: https://www.simz.dev/
