# snarkjs Fork

This repository is a fork of the original [snarkjs](https://github.com/iden3/snarkjs) project. The primary modification in this fork is the use of BLAKE2b as the hash function for the final beacon stage.

## Purpose

This fork was created to support [the trusted setup ceremony for our zkTrue-up product](https://github.com/term-structure/zkTrue-up-trusted-setup). To ensure correct verification results, it is necessary to use this fork when verifying the ceremony.

## Key Changes

*   **Hash Function**: Replaced the default hash function with BLAKE2b for the final beacon stage.
    *   [commit](https://github.com/term-structure/snarkjs/commit/45f796de4e974d9be8d3eab66bd615a87904b733)

## Usage

The usage of this fork remains largely consistent with the original snarkjs project, with the primary difference being the hash function used in the final beacon stage. Users can refer to the original [snarkjs documentation](https://github.com/iden3/snarkjs) for general usage instructions.

## License

This project is licensed under the same terms as the original snarkjs. See the [COPYING](COPYING) file for details.
