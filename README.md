# Post-Quantum Secure Cryptographic Algorithms 

Post-Quantum Secure Cryptographic Algorithms offer security against attacks by advanced binary and quantum technologies. They cover the whole CIA-spectre:

**C**onfidentiality: Key Exchanges, Encryption, Message Authentication
**I**ntegrity: Message Authentication, Signatures
**A**ccessibility: Effective Implementations

The article [Post-Quantum Secure Cryptographic Algorithms](https://github.com/XeniaGabriela/pq_for_ca/car_article.pdf) outlines the state of Post-Quantum Secure Cryptographic Algorithms in 2018. It was published in the *Computeralgebra Rundbrief* in fall 2018, in order to update the community of computer algebra experts, which consists of computer scientists and mathematicians. Nevertheless it can also be used as a guideline for a suitable choice of algorithm in this area by other interested readers.

## Why Computer Algebra?

Computer algebra refers to symbolic computation, meaning exact computation with mathematical expressions and objects containing variables that have no given value and are manipulated as symbols. Therefore computer algebra is generally considered as a distinct field from scientific computing, which is usually based on numerical computation with approximate floating point numbers.  

## Replacement for Integer Factorization and Discrete Logarithm

The security of the mentioned algorithms relies on the hardness of chosen problems in the following mathematical areas:

* Coding theory
* Lattice problems
* Hash functions (signatures only)
* Multivariate polynomials
* Isogenies

Neither of them rely on the integer factorization or discrete logarithm problem, which will be computable in reasonable time with potent enough quantum computers.

## Post-Quantum Cryptography vs. Quantum Key Distribution

Quantum Key Distribution is a protocol for key exchange based on foundations of quantum mechanics. Its limitations are clearly outlined in the following [Whitepaper](https://www.ncsc.gov.uk/whitepaper/quantum-key-distribution).

The advantages of Post-Quantum secure algorithms against Quantum Key Distribution are

* Effective implementation and performance on currently used devices
* Dynamic message authentication 
* Verification of identities
* Verification of data integrity
* Establishment of network sessions 
* Access control
* Automatic software updates
* Restoration of comprised systems by pure software updates
* Well understood in terms of potential attacks

## Necessity

The expected dawn of a new technological era has certainly begun when IBM offered their first commercially available 20-Qubit Quantum Computers November 2017. While it was still discussed if it was necessary to take quantum technology into account in the IT industry during 2017, the estimations about their capability evolvement become much more specific in 2018.

Luckily scientific researchers have specialized in the examinations of the various resulting challenges and questions since the beginning of this century. A series of conferences about post-quantum cryptography, the PQCrypto, started in 2006. Since 2010, they take place in another town of the world every year. The following article gives an overview of current developments in algorithmic solutions answering the upcoming threats posed by quantum computers as well as unsolved problems in the classical IT landscape.

## Standardization

The NIST standardization process of post-quantum secure algorithms has started in 2017 and is expected to be finalized by 2021/22.

## Contributors

Dipl. Math. Xenia Bogomolec, X4pi GmbH
Dr. Jochen Gerhard, BearingPoint Software Solutions GmbH