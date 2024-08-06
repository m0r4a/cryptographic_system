# Cryptographic system

🇲🇽  [ Versión en español](/README_es.md)

## Summary

An application will be developed to store encrypted and signed information, ensuring identification of the user who stored it using digital certificates.

## Functionality

The application should:

1. Start by asking if the user wants to register (create a new certificate) or log in (read an existing certificate).

2. The certificate must be saved as two files (public key / private key), with the private key encrypted by a password.

3. It must be able to store information encrypted with the user's certificates.

4. A blockchain or elliptic curve system will be used for key generation.

5. It must include at least three cryptographic systems: one symmetric, one asymmetric, and one of free choice (as required by the student).

6. Optionally, a simple DApp can be created to allow information storage (still, it must comply with point number 2).

## Details

| Description                                           | Points |
|-------------------------------------------------------|:------:|
| Symmetric encryption method                           |   10   |
| Asymmetric encryption method                          |   10   |
| Free encryption method (different from the two above) |   10   |
| Use of public key/private key                         |   10   |
| Saving certificates to a file                         |   10   |
| Use of blockchain or elliptic curve keys              |   15   |
| Information signing                                   |   15   |
| User identification by certificate                    |   20   |
| Creation of DApp (Optional)                           |   15   |
