# External Secrets Operator

This project was born as a kind of PoC of adding easily the needed operator-sdk envelope to current [helm chart external-secrets operator](https://github.com/external-secrets/external-secrets) without doing any change on the existing helm chart operator, so the operator could be installed natively through OLM (Operator Lifecyle Manager).

This PoC project was donated to the [external-secrets community](https://github.com/external-secrets) in upstream issue https://github.com/external-secrets/external-secrets/issues/493, so ESO maintainers were able to do releases of both helm charts and OLM operator at [OperatorHub.io](https://operatorhub.io).

The donation was done via fork, and it is actively maintained at https://github.com/external-secrets/external-secrets-helm-operator