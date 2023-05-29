# Post-Quantum Secure Cryptographic Algorithms

Version 2.0 of this article is published within the online version of [The Digital Journey of Banking and Insurance, Volume II pp 189-199](https://link.springer.com/chapter/10.1007/978-3-030-78829-2_11).

## What is Post-Quantum Cryptography?

Post-quantum secure cryptographic algorithms offer security against attacks by advanced binary and quantum technologies. They cover the whole CIA-spectre:

* **C**onfidentiality: key exchanges, encryption, message authentication
* **I**ntegrity: message authentication and signatures
* **A**vailabilty: effective implementations on currently used devices allow systems to operate efficiently while integrating post-quantum secure cryptography  

## Mathematical Ways to Meet Evolving Technology Threats

Private keys of a an asymmetric cryptosystem relying on the discrete logarithm or integer factorization will be computable in feasible time from the related public key, as soon as potent enough quantum computers are available.

The security of post-quantum secure cryptographic algorithms relies on the hardness of chosen problems in the following mathematical areas:

* Coding theory
* Lattice problems
* Hash functions (signatures only)
* Multivariate polynomials
* Isogenies
* Module Learning With Rounding problem (MLWR)
* etc.

Neither of them rely on the integer factorization or discrete logarithm problem, for which Shor's Algorithm offers a quantum cryptanalysis.

## Necessity of Post-Quantum Cryptography

The expected dawn of a new technological era has certainly begun when IBM offered their first commercially available 20-Qubit Quantum Computers November 2017. While it was still discussed if it was necessary to take quantum technology into account in the IT industry during 2017, the estimations about their capability evolvement become touchable every year. 

IBM had announced to create a 1000 qubit universal quantum processor until 2023. A [433 qubit processor]( https://newsroom.ibm.com/2022-11-09-IBM-Unveils-400-Qubit-Plus-Quantum-Processor-and-Next-Generation-IBM-Quantum-System-Two) has been realized in 2022. The ability of quantum computing devices to solve problems that classical computers practically cannot solve is no longer  theory alone, despite of challenges to Quantum computing such as errors and decoherence.

Luckily scientific researchers have specialized in the examinations of the various resulting challenges and questions since the beginning of this century. A series of conferences about post-quantum cryptography, the PQCrypto, started in 2006. Since 2010, they take place in another town of the world every year. The article [Post-Quantum Secure Cryptographic Algorithms](https://github.com/XeniaGabriela/pq_for_ca/blob/master/car_article.pdf) gives an overview of current developments in algorithmic solutions answering the upcoming threats posed by quantum computers as well as unsolved problems in the classical IT landscape.

## Post-Quantum Cryptography vs. Quantum Key Distribution

Quantum Key Distribution offers various protocols for a symmetric key exchange based on foundations of quantum mechanics. Their scope and limitations are clearly outlined in the following [Whitepaper](https://www.ncsc.gov.uk/whitepaper/quantum-key-distribution).

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

The advantages of QKD on the other side is unconditional security wrt. confidentiality - authenticity needs to be realized with conditionally secure measures.
In the case of the so-called discrete QKD, this concerns the information exchange via the public channel in particular.
Furthermore, a wide variety of key exchange methods will offer more fallback possibilities in case of a post-quantum key exchange or an application thereof is deprecated.

## Post-Quantum Cryptography Standardization

The NIST standardization process of post-quantum secure algorithms has started in 2017 and is expected to be finalized by 2021/22.

## Purpose of the published Article

The article [Post-Quantum Secure Cryptographic Algorithms](https://github.com/XeniaGabriela/pq_for_ca/blob/master/car_article.pdf) outlines the state of post-quantum secure cryptographic algorithms in 2018. It was published in the *Computeralgebra Rundbrief* in fall 2018, in order to update the community of computer algebra experts, which consists of computer scientists and mathematicians. 

**Nevertheless it can also be used as a guideline for a suitable choice of algorithm in this area by other interested readers!**

Don't hesitate to contact us for further questions: 
* Xenia Bogomolec: [xb@quant-x-sec.com](xb@quant-x-sec.com)
* Jochen Gerhard: [jochen.gerhard@fias.uni-frankfurt.de](jochen.gerhard@fias.uni-frankfurt.de)

## Why was the Article published in the Context of Computeralgebra?

Post-Quantum secure cryptographic algorithms are scientific subjects of computeralgebra, which refers to symbolic computation, meaning exact computation with mathematical expressions and objects containing variables that have no given value and are manipulated as symbols. Therefore computer algebra is generally considered as a distinct field from scientific computing, which is usually based on numerical computation with approximate floating point numbers.  

Parameter choices are much more delicate for post-quantum crypto schemes than they are for classical ones. Furthermore classical asymmetric schemes mostly rely on number theory, a topic which has been studied in early courses at universities, where post-quantum algorithms include more mathematics from courses which are usually taught at later stages of study courses.

Therefore there will be an increased need of cooperations between mathematicians, computer scientists and programmers to mitigate flaws in implementations, configurations and applications. The authors' intention was to raise this awareness in the computer algebra community to prepare the scientific backbone for future interactions to the industry and other operators.

## Authors of the Article

* Dipl. Math. Xenia Bogomolec, Quant-X Security & Coding GmbH
* Dr. Jochen Gerhard, Independent Scientific Author

