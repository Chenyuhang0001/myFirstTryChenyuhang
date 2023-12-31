# Security Policy

## Reporting a Vulnerability

To report security issues send an email to security@acinq.fr (not for support).

The following keys may be used to communicate sensitive information to developers:

| Name                | Fingerprint                                       |
|---------------------|---------------------------------------------------|
| Pierre-Marie Padiou | 6AA4 5A4C 209A 2D30 64CF 66BE E434 ED29 2E85 643A |
| Fabrice Drouin      | C25A 288A 842E AF7A A5B5 303F 7A73 FE77 DE2C 4027 |
| Bastien Teinturier  | 72BD 8AD9 F656 1619 37FA 8A5D 34F3 77B0 100E D6BB |

You can import keys by running the following commands:

```sh
gpg --keyserver https://acinq.co/pgp/padioupm.asc --recv-keys "6AA4 5A4C 209A 2D30 64CF 66BE E434 ED29 2E85 643A"
gpg --keyserver https://acinq.co/pgp/drouinf.asc --recv-keys "C25A 288A 842E AF7A A5B5 303F 7A73 FE77 DE2C 4027"
gpg --keyserver https://acinq.co/pgp/tbast.asc --recv-keys "72BD 8AD9 F656 1619 37FA 8A5D 34F3 77B0 100E D6BB"
```

Ensure that you put quotes around fingerprints containing spaces.
