# jwks-generator
Simple x5t validator for JWK Set URL and generator for certificate file.

# Usage

## Validate x5t from URL

It checks if the x5t and x5t#S256 are validate.

```
./validate-x5t.sh [URL]
```

## Generate JWK from file.crt

It generates JWK file from a certificate file and prints the output.

```
./generate-jwk.sh [FILE CERT]
```
