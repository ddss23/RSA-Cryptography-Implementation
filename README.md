
# **RSA Cryptography Implementation**
This GitHub repository contains the implementation of the INSE6110 project, focusing on the Simple RSA encryption and decryption, as well as signature and verification processes.

## Project Overview
### Part 1: Simple RSA (Encryption and Decryption)
**Project Objective:**
Understand the RSA algorithm and implement a basic version without relying on pre-built modules like the RSA module in Python.

**Parameter Selection:**
Randomly select two prime numbers, p and q, each with 16 bits. <br>
Compute N = p * q. <br>
Compute Phi(N) = (p - 1) * (q - 1). <br>
Randomly select a public key, e, such that e < Phi(N) and e is coprime to Phi(N) (gcd(e, Phi(N)) = 1). <br>
Find the corresponding private key, d, such that (e * d) mod Phi(N) = 1. <br>
Publish the public key (N, e) on the designated database on Moodle. <br>
Encryption/Decryption:
Write functions to encrypt and decrypt messages using the square and multiply algorithm.<br>

**Encryption:**

Send an encrypted message to your project partner.<br>
Check your partner's name on Moodle.<br>
Retrieve your partner's public key (N, e).<br>
Choose a small message (m) such that m < N.<br>
Encrypt the message using your partner's public key. <br>
Publish the encrypted message on the designated database on Moodle.<br>

**Decryption:**

Check your partner's database and retrieve the encrypted message.<br>
Use your private key (d) to decrypt the received message.<br>
Publish the decrypted message on the designated database on Moodle.<br>

### Part 2: Signature/Verification
**Signature:**
Sign your name without hashing using your private key (d).<br>
Publish the signature along with your name on the designated database on Moodle.<br>
**Verification:**
Use your partner's public key (N, e) and their name to verify their signature.

## How to Use
Implement the Simple RSA algorithm by following the provided specifications.<br>
Execute the encryption and decryption functions for secure message exchange.<br>
Implement the signature and verification functions for secure message signing and verification.<br>
Publish and retrieve keys, encrypted messages, and signatures on the designated databases on Moodle.<br>


Note: Ensure responsible and ethical usage of encryption and signing techniques. Unauthorized actions are strictly prohibited.
