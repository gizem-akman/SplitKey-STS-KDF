# ProVerif Implementation of STS-KDF and Split-Key STS-KDF variants

This project is developed in Secure System Group, University of Helsinki, by Gizem Akman, Mohamed Taoufiq Damir, Philip Ginzboorg, Sampo Sovio, and Valtteri Niemi. 

## Objective

This project aims to implement formal verifications in ProVerif for following protocols:

1. Station-to-Station protocol with Key Derivation Function (STS-KDF)
2. Privacy-Enhanced STS-KDF Certificate-Binding (STS-KDF-CB) Protocol
3. Privacy-Enhanced STS-KD-CB Protocol with Key Encapsulation Mechanism (KEM)
4. Split-Key Privacy-Enhanced STS-KDF-CB Protocol
5. Split-Key Privacy-Enhanced STS-KDF-CB Protocol with KEM

## Content

We provide Formal Verification codes for the following:

### Protocol Models
**stskdf.pv** - STS-KDF Protocol

**stskdf_cb.pv** - Privacy-Enhanced STS-KDF-CB Protocol

**stskdf_cb_kem.pv** - Privacy-Enhanced STS-KDF-CB Protocol with KEM

**TwoSplit_stskdf_cb.pv** - Split-Key Privacy-Enhanced STS-KDF-CB Protocol

**TwoSplit_stskdf_cb_kem.pv** - Split-Key Privacy-Enhanced STS-KDF-CB Protocol with KEM

### Reflection Attack
**stskdf_attack.pv** - Reflection attack construction on STS-KDF Protocol

**stskdf_cb_attack.pv** - Reflection attack construction on Privacy-Enhanced STS-KDF-CB Protocol

**stskdf_cb_kem_attack.pv** - Reflection attack construction on Privacy-Enhanced STS-KDF-CB Protocol with KEM

**TwoSplit_stskdf_cb_attack.pv** - Reflection attack construction on Split-Key Privacy-Enhanced STS-KDF-CB Protocol

**TwoSplit_stskdf_cb_kem_attack.pv** - Reflection attack construction on Split-Key Privacy-Enhanced STS-KDF-CB Protocol with KEM

## ProVerif

ProVerif is a state-of-art tool for formal verification for the symbolic modeling and analysis of security protocols. It uses Dolev-Yao as an adversary model. ProVerif uses the applied pi-calculus as a formal language, and translates the protocol into a set of Horn clauses, then tries to conclude if some security property is falsified, i.e., finds an attack.

For more information, [Proverif Manual](https://bblanche.gitlabpages.inria.fr/proverif/manual.pdf) is available online.

## Contact

Corresponding author is Gizem Akman. You can contact via gizem [dot] akman [at] helsinki [dot] fi.

