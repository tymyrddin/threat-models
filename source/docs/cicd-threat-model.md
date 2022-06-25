# CI/CD threat model

CI/CD pipelines were conceptualised with speed and convenience (and profit) in mind, not security. How wonderful for
adversaries!

DevOps threat modelling is easy to do for simple, monolithic applications,
less so when it is scaled up and migrated to the cloud, and an application team is responsible for full-stack management
in ever faster Software Development Life Cycles (SDLC). It is not so much that the type of attacks have changed, but the
attack surface and number of planes and access points have increased, while the time spent on considering security
vulnerabilities has decreased.

Common problems:

- Relying on routines and named processes for threat modelling can result in inadequate investments, overconfidence and increased vulnerability to attacks.
- Entry points to publicly-exposed management planes, APIs and services and their trust boundaries may not be recognised as vulnerable.
- An adversary possessing a permissioned authentication token can threaten a cloud service provider’s publicly-exposed control plane.
- Infrastructure as Code (IaC) evolved to solve the problem of environment drift in the release pipeline, and can make the infrastructure configuration available to a CI/CD application pipeline.
- The increasing consumption of secrets by CI/CD pipelines introduces complexities, making it difficult to store, transmit, and audit secrets securely.

## Workflows

* [Application code workflows](https://tymyrddin.github.io/cicd-threat-model/docs/workflows/application.html)
* [Infrastructure code workflows](https://tymyrddin.github.io/cicd-threat-model/docs/workflows/infrastructure.html)

## Adversaries

* [External adversary](https://tymyrddin.github.io/cicd-threat-model/docs/adversaries/external.html)
* [Internal adversary](https://tymyrddin.github.io/cicd-threat-model/docs/adversaries/internal.html)

## Assets

* [CI server access control](https://tymyrddin.github.io/cicd-threat-model/docs/assets/ci-access.html)
* [Database](https://tymyrddin.github.io/cicd-threat-model/docs/assets/database.html)
* [Source code management access control](https://tymyrddin.github.io/cicd-threat-model/docs/assets/scm-access.html)
* [Source code](https://tymyrddin.github.io/cicd-threat-model/docs/assets/source-code.html)

## Attack vectors

* [Authentication schemes](https://tymyrddin.github.io/cicd-threat-model/docs/attack-vectors/authentication-schemes.html)
* [CI Server](https://tymyrddin.github.io/cicd-threat-model/docs/attack-vectors/ci-server.html)
* [Containers](https://tymyrddin.github.io/cicd-threat-model/docs/attack-vectors/containers.html)
* [K8s objects](https://tymyrddin.github.io/cicd-threat-model/docs/attack-vectors/k8s-objects.html)
* [Logs](https://tymyrddin.github.io/cicd-threat-model/docs/attack-vectors/logs.html)
* [Package registries](https://tymyrddin.github.io/cicd-threat-model/docs/attack-vectors/package-registries.html)
* [Repository hosting services](https://tymyrddin.github.io/cicd-threat-model/docs/attack-vectors/repo-hosting-services.html)

## Attacks

* [Poisoned pipeline execution](https://tymyrddin.github.io/cicd-threat-model/docs/attacks/ppe.html)
* [Supply chain attacks](https://tymyrddin.github.io/cicd-threat-model/docs/attacks/sca.html)

## Threats

* [Exposure of secrets](https://tymyrddin.github.io/cicd-threat-model/docs/threats/exposure-secrets.html)
* [Insecure code](https://tymyrddin.github.io/cicd-threat-model/docs/threats/insecure-code.html)
* [Insecure system configuration](https://tymyrddin.github.io/cicd-threat-model/docs/threats/insecure-system-config.html)
* [Lateral movement](https://tymyrddin.github.io/cicd-threat-model/docs/threats/lateral-movement.html)
* [Usage of third party services](https://tymyrddin.github.io/cicd-threat-model/docs/threats/third-party.html)
