# Digital Signature - Bartosz Chwilkowski

This repository contains Python scripts for generating random numbers and implementing RSA encryption and digital signatures.

## Random Number Generation

The script uses the `psutil` and `mmh3` libraries to generate random numbers. The CPU frequency is used as a seed for the MurmurHash function to generate random numbers.

## RSA Encryption

The RSA script uses the `rsa` library to generate RSA key pairs, encrypt messages, and decrypt messages. The random number generator from the previous script is used as the source of randomness for key generation.

## Digital Signature

The digital signature script uses the `hashlib` and `binascii` libraries to hash messages and compare them. It demonstrates the use of the RSA keys generated in the previous script to encrypt and decrypt hashed messages.

## Usage

1. Run the random number generator script to generate random numbers.
2. Run the RSA script to generate RSA key pairs and encrypt/decrypt messages.
3. Run the digital signature script to hash messages and compare them.

## Note

The scripts are for educational purposes and should not be used for real-world encryption as they may not provide a sufficient level of security.
