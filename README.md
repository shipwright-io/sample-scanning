# sample-scanning

This sample provides two Dockerfiles

```
Dockerfile.good
Dockerfile.bad
```

The `good` Dockerfile being guarenteed to have no CVEs (it's just `scratch`) and the `bad` Dockerfile being an old image which `trivy` will report to have a critical CVE.
