# Demo for Renovate against a NPM hosted Google Artifact Registry

1. Key created with following command:
```
cat sap-cto-architecture-0b423c22f96d.json | base64
```

2. Copy output (without new line) into https://app.renovatebot.com/encrypt

3. Ensure that the service account has `Artifact Registry Reader` on the given Google Artifact Repository
