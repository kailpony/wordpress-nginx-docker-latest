# SSL - certificates for development

SSL development certificates are included in this repository for demonstration purposes and should be replaced with genuine certificates in production.

- `privkey.pem`  : the private key for your certificate.
- `fullchain.pem`: the certificate file used in most server software (copy of chain.pem for development purposes).

These certificates are self signed, and as such not reckognized by any CA. Do not use this for anything beyond local development (Never use in production)

