# Threat models

Bottom-up and top-down, with intent to create human-readable threat modelling examples. A work in progress.

## Common problems

- Many threat modeling processes are available, which can lead to confusion, especially for teams relying on routines and named processes. This can lead to inadequate or inappropriate cybersecurity investments, or worse, overconfidence in security posture and risk mitigation capabilities, which increases vulnerability to attacks.
- Threat modelling is easy to do for simple, monolithic applications, less so when it is scaled up and migrated to the cloud, and an application team is responsible for full-stack management.
- Entry points and trust boundaries are not recognised, like publicly-exposed management planes, APIs and services.
- An attacker that possesses a properly permissioned authentication token can easily threaten a cloud service provider’s publicly-exposed control plane.

It is not so much that the attacks have changed, attack surface has increased and is distributed with many endpoints. Over [70% of security vulnerabilities exist at the application layer](https://cdn2.hubspot.net/hub/49125/file-14369608-pdf).

