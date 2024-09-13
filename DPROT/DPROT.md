# Subject

- ECTS Credits: 5
- Final Grade: 7.3/10
- Total Learning Time: 125 hours

Description...

## Teaching Methodology

- Lectures
- Individual work
- Final Exam

## Learning Objectives

Understanding the necessary cryptographic techniques used to protect data during storage and transmision, in order to guarantee its
confidentiality, integrity and authentication

## Assignements

- **Lab 1** - RC4 Practical Attack
  - [Report](./DPORT_Lab1_RC4_Practical_Attack.pdf)
  - [Code](https://github.com/blueh0rse/rc4-breaker)

In this lab we propose a easy-to-implement key-recovery attack against a particular mode of operation of RC4.

- **Lab 2** - MAC forgery Attacks
  - [Report](./DPROT_Lab2_MAC_Forgery_Attacks.pdf)
  - [Code](https://github.com/blueh0rse/mac-forgery-attacks)

In this lab we developed a python script to recreate the CBC-MAC concatenation attack.

- **Lab 3** - Merkle Tree
  - [Report](./DPROT_Lab3_Merkle_Tree.pdf)
  - [Code](https://github.com/blueh0rse/build-merkle-tree)

In this lab we developed several scripts to performs action on merkle trees like creation, update, proof generation, proof verification.

- **Lab 4** - Public Key Encryption
  - [Report](./DPROT_Lab4_Public_Key_Encryption.pdf)
  - [Code](https://github.com/blueh0rse/pubk-enc)

In this lab we developed some scripts to simulate an encrypted message exchange between two people and to send an encrypted message to someone based on its public key.

- **Lab 5** - Digital Signatures
  - [Report](./DPROT_Lab5_Digital_Signatures.pdf)

In this lab we worked on digital signatures with `openssl`. We generated and verified certificates.

- **Final work** - [Quantum Key Exchange Paper](./DPROT_Project_Quantum_Key_Exchange_Paper.pdf)

This document introduces quantum cryptography, explaining key concepts such as Qubits, Quantum Key Distribution, and Quantum Key Exchange. It then explores various quantum key exchange protocols, including BB84, the E91 protocol, SARG04, and the B92 protocol. The document also addresses key threats and attacks, such as Photon Number Splitting, intercept and resend attacks, and Man-in-the-Middle attacks.

## Theory

1. Introduction  
   - Introduction to cryptography under the point of view of data protection.

2. Symmetric key  
   - Symmetric key encryption.  
   - Stream and block ciphers.  
   - Modes of operation.  
   - Message authentication codes.  
   - Hash functions.  
   - Authenticated encryption.

3. Public key  
   - Key Exchange.  
   - Public key encryption.  
   - Man-in-the-middle attacks.  
   - Digital signatures.  
   - Identification schemes.  
   - Public key certificates.  
   - Identity-based cryptography.

4. Security models  
   - Definition of easy and hard computational tasks.  
   - Security notions for encryption.  
   - Security notions for signatures.  
   - The random oracle model.  
   - Reductions and security proofs.

5. Zero-knowledge  
   - Zero-knowledge proofs and arguments.  
   - Non-interactive zero-knowledge.  
   - Applications.

6. Distributed cryptography  
   - Cryptography for many users.  
   - Secret sharing.  
   - Threshold decryption.  
   - Threshold signatures.  
   - Secure multiparty computation.

7. Case study  
   - Study of real cryptographic protocols used in some practical scenarios.
