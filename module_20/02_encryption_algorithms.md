# Section 02: Encryption Algorithms

## Encryption Algorithms
Encryption
> In cryptography, encryption is the process of encoding information. This process converts the original representation of the information, known as plaintext, into an alternative form known as ciphertext. Ideally, only authorized parties can decipher a ciphertext back to plaintext and access the original information. Encryption does not itself prevent interference but denies the intelligible content to a would-be interceptor.

Cipher
> In cryptography, a cipher (or cypher) is an algorithm for performing encryption or decryption—a series of well-defined steps that can be followed as a procedure.

Substitution cipher
> In cryptography, a substitution cipher is a method of encrypting in which units of plaintext are replaced with the ciphertext, in a defined manner, with the help of a key; the "units" may be single letters (the most common), pairs of letters, triplets of letters, mixtures of the above, and so forth. The receiver deciphers the text by performing the inverse substitution process to extract the original message.

An example of a substitution cipher is the Caesar cipher.

Transposition cipher
> In cryptography, a transposition cipher is a method of encryption which scrambles the positions of characters (transposition) without changing the characters themselves.

Block cipher
> In cryptography, a block cipher is a deterministic algorithm operating on fixed-length groups of bits, called blocks. They are specified elementary components in the design of many cryptographic protocols and are widely used to encrypt large amounts of data, including in data exchange protocols. It uses blocks as an unvarying transformation.

Stream cipher
> A stream cipher is a symmetric key cipher where plaintext digits are combined with a pseudorandom cipher digit stream (keystream).

DES (Data encryption standard)
> The Data Encryption Standard (DES /ˌdiːˌiːˈɛs, dɛz/) is a symmetric-key algorithm for the encryption of digital data.
> Although its short key length of 56 bits makes it too insecure for modern applications, it has been highly influential in the advancement of cryptography.

3DES (Triple DES)
> In cryptography, Triple DES (3DES or TDES), officially the Triple Data Encryption Algorithm (TDEA or Triple DEA), is a symmetric-key block cipher, which applies the DES cipher algorithm three times to each data block.

AES (Advanced encryption standard)
> The Advanced Encryption Standard (AES), also known by its original name Rijndael (Dutch pronunciation: [ˈrɛindaːl]), is a specification for the encryption of electronic data established by the U.S. National Institute of Standards and Technology (NIST) in 2001.

RC4 (Rivest cipher 4)
> In cryptography, RC4 (Rivest Cipher 4, also known as ARC4 or ARCFOUR, meaning Alleged RC4, see below) is a stream cipher.
> While it is remarkable for its simplicity and speed in software, multiple vulnerabilities have been discovered in RC4, rendering it insecure.

RC5 (Rivest cipher 5)
> In cryptography, RC5 is a symmetric-key block cipher notable for its simplicity.
> Designed by Ronald Rivest in 1994, RC stands for "Rivest Cipher", or alternatively, "Ron's Code" (compare RC2 and RC4).
> The Advanced Encryption Standard (AES) candidate RC6 was based on RC5.

RC6 (Rivest cipher 6)
> In cryptography, RC6 (Rivest cipher 6) is a symmetric key block cipher derived from RC5.
> It was designed by Ron Rivest, Matt Robshaw, Ray Sidney, and Yiqun Lisa Yin to meet the requirements of the Advanced Encryption Standard (AES) competition.

Blowfish
> Blowfish is a symmetric-key block cipher, designed in 1993 by Bruce Schneier and included in many cipher suites and encryption products.
> Blowfish provides a good encryption rate in software, and no effective cryptanalysis of it has been found to date.

Twofish
> In cryptography, Twofish is a symmetric key block cipher with a block size of 128 bits and key sizes up to 256 bits.
> It was one of the five finalists of the Advanced Encryption Standard contest, but it was not selected for standardization.

Threefish
> Threefish is a symmetric-key tweakable block cipher designed as part of the Skein hash function, an entry in the NIST hash function competition.

Serpent
> Serpent is a symmetric key block cipher that was a finalist in the Advanced Encryption Standard (AES) contest, where it was ranked second to Rijndael.
> Serpent was designed by Ross Anderson, Eli Biham, and Lars Knudsen.

TEA (Tiny encryption algorithm)
> In cryptography, the Tiny Encryption Algorithm (TEA) is a block cipher notable for its simplicity of description and implementation, typically a few lines of code.
> It was designed by David Wheeler and Roger Needham of the Cambridge Computer Laboratory; it was first presented at the Fast Software Encryption workshop in Leuven in 1994, and first published in the proceedings of that workshop.

RSA (Rivest shamir adleman)
> RSA (Rivest–Shamir–Adleman) is a public-key cryptosystem that is widely used for secure data transmission.
> It is also one of the oldest.
> The acronym "RSA" comes from the surnames of Ron Rivest, Adi Shamir and Leonard Adleman, who publicly described the algorithm in 1977.

Diffie Hellman
> Diffie–Hellman key exchange[nb 1] is a method of securely exchanging cryptographic keys over a public channel and was one of the first public-key protocols as conceived by Ralph Merkle and named after Whitfield Diffie and Martin Hellman.

MD5 (Message digest 5)
> The MD5 message-digest algorithm is a cryptographically broken but still widely used hash function producing a 128-bit hash value. Although MD5 was initially designed to be used as a cryptographic hash function, it has been found to suffer from extensive vulnerabilities.

SHA (Secure hash algorithm)
> The Secure Hash Algorithms are a family of cryptographic hash functions published by the National Institute of Standards and Technology (NIST) as a U.S. Federal Information Processing Standard (FIPS), including SHA-0, SHA-1, SHA-2 and SHA-3.

HMAC
> In cryptography, an HMAC (sometimes expanded as either keyed-hash message authentication code or hash-based message authentication code) is a specific type of message authentication code (MAC) involving a cryptographic hash function and a secret cryptographic key.

Elliptic-curve cryptography
> Elliptic-curve cryptography (ECC) is an approach to public-key cryptography based on the algebraic structure of elliptic curves over finite fields.
> ECC allows smaller keys compared to non-EC cryptography (based on plain Galois fields) to provide equivalent security.

Quantum cryptography
> Quantum cryptography is the science of exploiting quantum mechanical properties to perform cryptographic tasks.
> The best known example of quantum cryptography is quantum key distribution which offers an information-theoretically secure solution to the key exchange problem.

Homomorphic encryption
> Homomorphic encryption is a form of encryption that permits users to perform computations on its encrypted data without first decrypting it.

Trusted platform module
> Trusted Platform Module (TPM, also known as ISO/IEC 11889) is an international standard for a secure cryptoprocessor, a dedicated microcontroller designed to secure hardware through integrated cryptographic keys.

Hardware security module
> A hardware security module (HSM) is a physical computing device that safeguards and manages digital keys, performs encryption and decryption functions for digital signatures, strong authentication and other cryptographic functions.

Block cipher mode of operation
> In cryptography, a block cipher mode of operation is an algorithm that uses a block cipher to provide information security such as confidentiality or authenticity.

ECB (Electronic code book) mode
> The simplest (and not to be used anymore) of the encryption modes is the electronic codebook (ECB) mode (named after conventional physical codebooks).
> The message is divided into blocks, and each block is encrypted separately.

Cipher block chaining
> Ehrsam, Meyer, Smith and Tuchman invented the cipher block chaining (CBC) mode of operation in 1976.
> In CBC mode, each block of plaintext is XORed with the previous ciphertext block before being encrypted.
> This way, each ciphertext block depends on all plaintext blocks processed up to that point.

MAC (Message authentication code)
> In cryptography, a message authentication code (MAC), sometimes known as a tag, is a short piece of information used for authenticating a message.
> In other words, to confirm that the message came from the stated sender (its authenticity) and has not been changed.

Blockchain
> A blockchain is a type of distributed ledger technology (DLT) that consists of growing list of records, called blocks, that are securely linked together using cryptography.

Public blockchain
> A public blockchain has absolutely no access restrictions.
> Anyone with an Internet connection can send transactions to it as well as become a validator (i.e., participate in the execution of a consensus protocol).
> Usually, such networks offer economic incentives for those who secure them and utilize some type of a Proof of Stake or Proof of Work algorithm.

Private blockchain
> A private blockchain is permissioned.
> One cannot join it unless invited by the network administrators.
> Participant and validator access is restricted.
> To distinguish between open blockchains and other peer-to-peer decentralized database applications that are not open ad-hoc compute clusters, the terminology Distributed Ledger (DLT) is normally used for private blockchains.

Links
- [https://en.wikipedia.org/wiki/Encryption](https://en.wikipedia.org/wiki/Encryption)
- [https://en.wikipedia.org/wiki/Cipher](https://en.wikipedia.org/wiki/Cipher)
- [https://en.wikipedia.org/wiki/Substitution_cipher](https://en.wikipedia.org/wiki/Substitution_cipher)
- [https://en.wikipedia.org/wiki/Caesar_cipher](https://en.wikipedia.org/wiki/Caesar_cipher)
- [https://en.wikipedia.org/wiki/Transposition_cipher](https://en.wikipedia.org/wiki/Transposition_cipher)
- [https://en.wikipedia.org/wiki/Stream_cipher](https://en.wikipedia.org/wiki/Stream_cipher)
- [https://en.wikipedia.org/wiki/Data_Encryption_Standard](https://en.wikipedia.org/wiki/Data_Encryption_Standard)
- [https://en.wikipedia.org/wiki/Triple_DES](https://en.wikipedia.org/wiki/Triple_DES)
- [https://en.wikipedia.org/wiki/Advanced_Encryption_Standard](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard)
- [https://en.wikipedia.org/wiki/RC4](https://en.wikipedia.org/wiki/RC4)
- [https://en.wikipedia.org/wiki/RC5](https://en.wikipedia.org/wiki/RC5)
- [https://en.wikipedia.org/wiki/RC6](https://en.wikipedia.org/wiki/RC6)
- [https://en.wikipedia.org/wiki/Blowfish_(cipher)](https://en.wikipedia.org/wiki/Blowfish_(cipher))
- [https://en.wikipedia.org/wiki/Twofish](https://en.wikipedia.org/wiki/Twofish)
- [https://en.wikipedia.org/wiki/Threefish](https://en.wikipedia.org/wiki/Threefish)
- [https://en.wikipedia.org/wiki/Serpent_(cipher)](https://en.wikipedia.org/wiki/Serpent_(cipher))
- [https://en.wikipedia.org/wiki/Tiny_Encryption_Algorithm](https://en.wikipedia.org/wiki/Tiny_Encryption_Algorithm)
- [https://en.wikipedia.org/wiki/RSA_(cryptosystem)](https://en.wikipedia.org/wiki/RSA_(cryptosystem))
- [https://en.wikipedia.org/wiki/Diffie%E2%80%93Hellman_key_exchange](https://en.wikipedia.org/wiki/Diffie%E2%80%93Hellman_key_exchange)
- [https://en.wikipedia.org/wiki/MD5](https://en.wikipedia.org/wiki/MD5)
- [https://en.wikipedia.org/wiki/Secure_Hash_Algorithms](https://en.wikipedia.org/wiki/Secure_Hash_Algorithms)
- [https://en.wikipedia.org/wiki/HMAC](https://en.wikipedia.org/wiki/HMAC)
- [https://en.wikipedia.org/wiki/Homomorphic_encryption](https://en.wikipedia.org/wiki/Homomorphic_encryption)
- [https://en.wikipedia.org/wiki/Trusted_Platform_Module](https://en.wikipedia.org/wiki/Trusted_Platform_Module)
- [https://en.wikipedia.org/wiki/Hardware_security_module](https://en.wikipedia.org/wiki/Hardware_security_module)
- [https://en.wikipedia.org/wiki/Blockchain](https://en.wikipedia.org/wiki/Blockchain)
