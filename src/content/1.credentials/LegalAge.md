# LegalAgeCredential

```json
{
    "@context": ["https://www.w3.org/2018/credentials/v1"],
    "type": ["VerifiableCredential", "LegalAgeCredential"],
    "credentialSubject": {
        "age_over_18": "true"
    },
    "id": "io.dizme.legalage#uuid",
    "issued": "2021-08-31T00:00:00Z",
    "issuer": {
        "id": "did:key:z6MkrHKzgsahxBLyNAbLQyB1pcWNYC9GmywiWPgkrvntAZcj",
        "image": {
            "id": "https://www.infocert.it/content/uploads/2021/09/logo.svg",
            "type": "Image"
        },
        "name": "Infocert",
        "country": "IT",
        "type": "Profile",
        "url": "https://www.infocert.it/"
    },
    "validFrom": "2021-08-31T00:00:00Z",
    "issuanceDate": "2021-08-31T00:00:00Z"
}
```

## Mapping example

```json
{
    "id": "<uuid>",
    "issuer": {
        "id": "<issuerDid>"
    },
    "credentialSubject": {
        "unique_id": "<uuid>"
    },
    "issuanceDate": "<timestamp>"
}
```