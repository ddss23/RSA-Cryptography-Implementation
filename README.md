
# **RSA Cryptography Implementation**
This GitHub repository contains the implementation of the INSE6110 project, focusing on the Simple RSA encryption and decryption, as well as signature and verification processes.

## Project Overview
### Part 1: Simple RSA (Encryption and Decryption)
**Project Objective:**
Understand the RSA algorithm and implement a basic version without relying on pre-built modules like the RSA module in Python.

**Parameter Selection:**
Randomly select two prime numbers, p and q, each with 16 bits.
Compute N = p * q.
Compute Phi(N) = (p - 1) * (q - 1).
Randomly select a public key, e, such that e < Phi(N) and e is coprime to Phi(N) (gcd(e, Phi(N)) = 1).
Find the corresponding private key, d, such that (e * d) mod Phi(N) = 1.
Publish the public key (N, e) on the designated database on Moodle.
Encryption/Decryption:
Write functions to encrypt and decrypt messages using the square and multiply algorithm.

**Encryption:**

Send an encrypted message to your project partner.
Check your partner's name on Moodle.
Retrieve your partner's public key (N, e).
Choose a small message (m) such that m < N.
Encrypt the message using your partner's public key.
Publish the encrypted message on the designated database on Moodle.

**Decryption:**

Check your partner's database and retrieve the encrypted message.
Use your private key (d) to decrypt the received message.
Publish the decrypted message on the designated database on Moodle.

### Part 2: Signature/Verification
**Signature:**
Sign your name without hashing using your private key (d).
Publish the signature along with your name on the designated database on Moodle.
**Verification:**
Use your partner's public key (N, e) and their name to verify their signature.

## How to Use
Implement the Simple RSA algorithm by following the provided specifications.
Execute the encryption and decryption functions for secure message exchange.
Implement the signature and verification functions for secure message signing and verification.
Publish and retrieve keys, encrypted messages, and signatures on the designated databases on Moodle.


Note: Ensure responsible and ethical usage of encryption and signing techniques. Unauthorized actions are strictly prohibited.
