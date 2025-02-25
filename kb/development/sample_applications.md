# Sample Applications

Mbed TLS supplies several sample applications that demonstrate common use cases of the API. **These are sample programs only and do not cover full functionality of the API, or all use cases!**

These examples are in the [*programs*](https://github.com/Mbed-TLS/mbedtls/tree/development/programs) folder, separated into subfolders according to their theme.  

For more information, check the applications' `usage`.

## *`aes`*

These example programs demonstrate the usage of the symmetric cipher API.
  
- `aescrypt2` - A sample application that performs authenticated encryption and decryption of a buffer, using `mbedtls_aes_crypt_ecb`, with AES-256. The application reads from a file, ciphers it and writes output to a file.

## *`pkey`*

These sample applications demonstrate the usage of asymmetric cryptography APIs for key exchange and message signing, verification, encryption and decryption.

- `pk_sign` - A reference application that demonstrates how to use the Public key-based signature creation, using the [`pk`](https://github.com/Mbed-TLS/mbedtls/blob/development/include/mbedtls/pk.h) wrapper APIs.
- `pk_verify` - A reference application that demonstrates how to use the Public key-based signature verification, using the [`pk`](https://github.com/Mbed-TLS/mbedtls/blob/development/include/mbedtls/pk.h) wrapper APIs.
- `rsa_sign_pss` - An application demonstrating how to create a signature with the [PKCS #1 v2.1](https://www.ietf.org/rfc/rfc3447.txt) padding scheme.
- `rsa_verify_pss` - An application demonstrating how to verify a signature with the [PKCS #1 v2.1](https://www.ietf.org/rfc/rfc3447.txt) padding scheme.

## *`random`*

These applications demonstrate how to use Mbed TLS TRNG and PRNG APIs.

- `gen_random_havege` - An application demonstrating how to use the HArdware Volatile Entropy Gathering and Expansion ([havege](http://www.irisa.fr/caps/projects/hipsor/)) entropy API.

## *`ssl`*

These applications demonstrate common use cases for the SSL\TLS stack APIs.  

**Note: These applications use the [Mbed TLS test root certificate](https://github.com/Mbed-TLS/mbedtls/blob/development/include/mbedtls/certs.h) and are meant to work with one another. To test the client applications with an external server, the root certificate needs to be set correctly by calling the [`mbedtls_ssl_conf_ca_chain()`](/api/ssl_8h.html#a85c3bb6b682ba361d13de1c0a1eb69fb). Alternatively, some applications allow to optionally set the CA root certificate file through the command-line. To test the server applications with external clients, they need to replace `mbedtls_x509_crt_parse()` with [`mbedtls_x509_crt_parse_file()`](/api/group__x509__module.html#gad4da63133d3590aa311488497d4c38ec) to read the server and CA certificates, as well as replacing `mbedtls_pk_parse_key()` with [`mbedtls_pk_parse_keyfile()`](/api/pk_8h.html#a935d710e542409462d0209f2381da83e).**

- `dtls_client` - A DTLS client demonstration program.
- `dtls_server` - A DTLS server demonstration program.
- `mini_client` - A minimal TLS client that uses minimal set of memory consumption. It should be used with `config-suite-b.h` or `config-ccm-psk-tls1_2.h` as the configuration files.
- `ssl_client1` - An SSL client demonstration program.
- `ssl_client2` - An SSL client demonstration program with certificate authentication.
- `ssl_fork_server` - An SSL server demonstration program using `fork()` for handling multiple clients.
- `ssl_mail_client` - An SSL client for SMTP servers.
- `ssl_pthread_server` - An SSL server demonstration program using `pthread` for handling multiple clients.
- `ssl_server` - An SSL server demonstration program.
- `ssl_server2` - A flexible SSL server demonstration, which accepts many different options for various use cases.

## *`test`*

These are some generic sample application, that can be used for testing.

- `benchmark` - Benchmark demonstration program.
- `ssl_cert_test` - SSL certificate functionality test.
- `udp_proxy` - Emulation for an unreliable UDP connection for DTLS testing.

## *`utils`*

Sample applications for the utility APIs:

- `pem2der` - Convert `PEM` to `DER`.
- `strerror` - A program that translates error code to error string.

## *`x509`*

These reference applications demonstrate usage of the `X.509` format standard.

- `cert_app` - An `X.509` certificate reading and verifying application.
- `cert_req` - An `X.509` certificate request (CSR) generation program.
- `cert_write` - An `X.509` certificate generation and signing reference application.
- `crl_app` - An `X.509` Certificate Revocation List (CRL) reading application.
- `req_app` - An `X.509` certificate request (CSR) reading application.
