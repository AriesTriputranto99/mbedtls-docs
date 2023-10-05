# Roadmap

**Note that the quarter when a feature is expected to be completed is based on very rough estimates of the effort involved and therefore can change. Items to be delivered beyond the current quarter may be pushed back, or change in scope.**

If you are interested in collaborating on any of the roadmap features or other features in the project, please mail [Mbed TLS](https://lists.trustedfirmware.org/mailman/listinfo/mbed-tls) or [PSA Crypto](https://lists.trustedfirmware.org/mailman/listinfo/psa-crypto) mailing lists.

**2023 CQ4 (In Development)**
* [Mbed TLS] [Code size optimisation (driver only build - Cipher and AEAD)](https://github.com/orgs/Mbed-TLS/projects/1#column-19075367)
* [Mbed TLS] [TLS1.3 early data](https://github.com/orgs/Mbed-TLS/projects/5#column-19369183) 
* [Mbed TLS] [TLS1.3 misc](https://github.com/orgs/Mbed-TLS/projects/5#column-19575625) 
* [PSA Crypto] [PSA Crypto Thread safe](https://github.com/orgs/Mbed-TLS/projects/5#column-19575625) 
* [PSA Crypto] [PBKDF2 PSA SW Implementation](https://github.com/orgs/Mbed-TLS/projects/1#column-18986190)

**2024 CQ1**
* [Mbed TLS] [3.6 LTS release](https://github.com/orgs/Mbed-TLS/projects/5#column-19576380)
* [PSA Crypto] [PSA Crypto repo for Crypto development](https://github.com/orgs/Mbed-TLS/projects/5#column-19622947) 
* [Mbed TLS] Mbed TLS4.0 Preparations  
* [PSA Crypto] [PBKDF2 PSA Driver Implementation](https://github.com/orgs/Mbed-TLS/projects/1#column-18986190)
<https://github.com/orgs/Mbed-TLS/projects/5#column-19622947>
* [PSA Crypto] PSA driver – Handle Opaque Persistent Key in Secure Element - Implementation

**2024 CQ2**
* [Mbed TLS] Mbed TLS4.0 Release
* [Mbed TLS] Mbed TLS uses PSA Crypto repository
* PAKE API investigation for SPAKE2+ 
  
**Future**
 * [PSA Crypto] Memory Optimizations (code size)
 * [Mbed TLS] [PSA Crypto 1.1 compliance](https://github.com/orgs/Mbed-TLS/projects/1#column-18732191)
 * [PSA Crypto] [Extended PSA Crypto v1.0 spec compliance](https://github.com/orgs/Mbed-TLS/projects/1#column-17950134)
 * [Mbed TLS] [TLS1.3 Continued](https://github.com/orgs/Mbed-TLS/projects/1#column-17950144)
 * [PSA Crypto][PSA Secure Element, Crypto Accelerator Support Enhancements](https://github.com/orgs/Mbed-TLS/projects/1#column-17950148)
 * [Raw Public Key Mode](https://github.com/Mbed-TLS/mbedtls/pull/3552)
 * [EdDSA](https://github.com/orgs/Mbed-TLS/projects/1#column-17950143)
 * [PSA Crypto] SHA3
 * [Mbed TLS] Performance Optimization - ECP and Bignum
 * [PSA Crypto] Clean up and Stabilization 
 * DTLS1.3 
 * [Mbed TLS] [PKCS7 Generation](<https://github.com/Mbed-TLS/mbedtls/pull/3970>)
 * Post Quantum Crypto

**Completed**
* [Mbed TLS] [Code size optimisation (driver only build - ECC)](<https://github.com/orgs/Mbed-TLS/projects/1#column-19391691>)
* [PSA Crypto] [Memory Optimizations (code size)](<https://github.com/orgs/Mbed-TLS/projects/1#column-19417159>)
* [Mbed TLS] [Mbed TLS3.5 Release](<https://github.com/orgs/Mbed-TLS/projects/1#column-19402885>)
* [PSA Crypto] [Publish PSA Crypto prototype repository](<https://github.com/orgs/Mbed-TLS/projects/1#column-19564389>)
* [Mbed TLS] Publish Threat Model
* [Mbed TLS] [Code size optimisation (driver only build - hashes inc. HMAC)](https://github.com/orgs/Mbed-TLS/projects/1#column-19083975)
* [Mbed TLS] [PKCS7 Parser](https://github.com/orgs/Mbed-TLS/projects/1#column-17950135)
* [PSA Crypto] [PSA Crypto restartable sign message](https://github.com/orgs/Mbed-TLS/projects/1#column-18883250)
* [PSA Crypto] [ECJ-PAKE PSA Implementation](https://github.com/orgs/Mbed-TLS/projects/1#column-18883296) 
* [Mbed TLS] [Connection ID DTLS1.2](https://github.com/Mbed-TLS/mbedtls/pull/6264)
* [Mbed TLS] [Use PSA: code size optimisation via PSA_CRYPTO_CONFIG - part1: symmetric](https://github.com/orgs/Mbed-TLS/projects/1#column-18883163)
* [Mbed TLS] [TLS/X.509​ - Use PSA Long term secret isolation](https://github.com/orgs/Mbed-TLS/projects/1#column-183383222)
* [Mbed TLS] [TLS1.3 PSK](https://github.com/orgs/Mbed-TLS/projects/1#column-17950145)
* [Mbed TLS] [Mbed TLS3.2](https://github.com/orgs/Mbed-TLS/projects/1#column-18338314)
* [Mbed TLS] [TLS1.3 server side](https://github.com/orgs/Mbed-TLS/projects/1#column-17950131)
* [Mbed TLS] TLS1.3 MVP
* [Mbed TLS] TLS/X.509​ - Use PSA Crypto APIs Fully​ - Phase1
* [Mbed TLS] SHA256/512 - Neon Optimization
* [Mbed TLS] New 2.x LTS
* [PSA Crypto] Support Missing PSA Crypto v1.0 APIs supported in MbedCrypto
* [PSA Crypto]​ M-AEAD Implementation
* [PSA Crypto]​ EdDSA API  Design 
* [PSA Crypto]​ PBKDF2 API  Design 
* [PSA Crypto]​ ECJPAKE API Design  ​
* DTLS-SRTP 
* Lucky13 Security Improvements 
* [PSA Crypto] PSA Crypto API implementation v1.0 Specification - Phase1
* Unified PSA Driver Interface - API Design and initial support
* [PSA Crypto] PSA driver – Handle Opaque Persistent Key in Secure Element - [Design](<https://github.com/Mbed-TLS/mbedtls/blob/development/docs/architecture/psa-storage-resilience.md>) 
* [Mbed TLS] [Use PSA: misc. gaps](https://github.com/orgs/Mbed-TLS/projects/1#column-18337954)
* [Bignum] [ECP Curves field reduction - NIST](https://github.com/orgs/Mbed-TLS/projects/1#column-17950163)







