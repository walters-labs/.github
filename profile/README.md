# Walters Labs

Research software in mathematics and scientific computing, primarily in Rust.

Projects include numerical tools, implementations accompanying research, and
educational experiments. See each repository for its intended use, verification,
and limitations.

## Featured tool

[SP 800-90B](https://github.com/walters-labs/sp-800-90b) provides Rust tools for
assessing noise-source min-entropy, with command-line interfaces and
allocation-free embedded health tests. Includes comparisons against NIST's
reference implementation. Not NIST-endorsed or certified.

## Mathematical and research software

- [ntt](https://github.com/walters-labs/ntt): Number theoretic transforms in Rust.
- [fft-dihedral](https://github.com/walters-labs/fft-dihedral) and
  [fft-dihedral-py](https://github.com/walters-labs/fft-dihedral-py): Fourier
  transforms on dihedral groups over finite fields, in Rust and Python.
- [fft-symmetric](https://github.com/walters-labs/fft-symmetric) and
  [fft-symmetric-py](https://github.com/walters-labs/fft-symmetric-py): Fourier
  transforms on symmetric groups over finite fields, in Rust and Python.
- [gr-ntru](https://github.com/walters-labs/gr-ntru) and
  [gr-ntru-py](https://github.com/walters-labs/gr-ntru-py): Experimental research
  cryptography exploring NTRU over group algebras, in Rust and Python.

## Educational implementations and experiments

- [mlkem-fips203](https://github.com/walters-labs/mlkem-fips203): Educational
  implementation of ML-KEM as specified in FIPS 203.
- [aes-block-cipher-modes](https://github.com/walters-labs/aes-block-cipher-modes):
  Educational implementations of AES and block cipher modes.
- [module-lwe](https://github.com/walters-labs/module-lwe): Module-LWE encryption
  in Rust.
- [ring-lwe](https://github.com/walters-labs/ring-lwe): Ring-LWE encryption in Rust.
- [PINN](https://github.com/walters-labs/PINN): Experiments with physics-informed
  neural networks for partial differential equations.
- [SIGINT](https://github.com/walters-labs/SIGINT): Signal-processing experiments.

The cryptographic implementations listed here, including GR-NTRU, are intended
for research and education. They have not been audited and are not intended for
production use.
