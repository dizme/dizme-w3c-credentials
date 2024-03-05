# PID

```json
{
    "@context": ["https://www.w3.org/2018/credentials/v1"],
    "type": ["VerifiableCredential", "PID"],
    "credentialSubject": {
        "family_name": "family_name", 
        "given_name": "given_name", 
        "birth_date": "birth_date", 
        "age_over_18": "age_over_18", 
        "age_over_NN": "age_over_NN", 
        "age_in_years": "age_in_years", 
        "age_birth_year": "age_birth_year",
        "unique_id": "uuid", 
        "family_name_birth": "family_name_birth",
        "given_name_birth": "given_name_birth", 
        "birth_place": "birth_place", 
        "birth_country": "birth_country",
        "birth_state": "birth_state", 
        "birth_city": "birth_city", 
        "resident_address": "resident_address",
        "resident_country": "resident_country",
        "resident_state": "resident_state",
        "resident_city": "resident_city", 
        "resident_postal_code": "resident_postal_code",
        "resident_street": "resident_street", 
        "resident_house_number": "resident_house_number",
        "gender": "gender", 
        "nationality": "nationality" 
    },
    "id": "identity#PID#uuid",
    "issued": "2021-08-31T00:00:00Z",
    "issuer": {
        "id": "did:key:z6MkrHKzgsahxBLyNAbLQyB1pcWNYC9GmywiWPgkrvntAZcj",
        "image": {
            "id": "https://www.infocert.it/content/uploads/2023/07/infocert-logo-white.svg",
            "type": "Image"
        },
        "name": "Infocert",
        "country": "IT",
        "type": "Profile",
        "url": "https://www.infocert.it"
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
        "unique_id": "<subjectDid>"
    },
    "issuanceDate": "<timestamp>"
}
```