# E2EE Messaging threat model

After Snowden’s revelation, E2EE received a lot of attentions as a technology to protect user privacy from mass interception and surveillance of communications carried out by governmental organizations such as NSA and GCHQ. Supposedly, end-to-end encryption (E2EE) is a defence against MitM attacks.

### Adversaries

- [E2EE adversary](e2ee/adversaries/E2EE-adversary.md)
- [Service provider](e2ee/adversaries/Service-provider.md)
- [Malicious user](e2ee/adversaries/Malicious-user.md)
- [Malicious group member](e2ee/adversaries/Malicious-group-member.md)
  
### Assets

- [Cipher](e2ee/assets/Cipher.md)
- [Messages/Emails](e2ee/assets/Messages-and-emails.md)
- [Keyrings](e2ee/assets/Keyrings.md)
- [Cloud/Storage Systems](e2ee/assets/Cloud-and-storage-systems.md)
- [Databases](e2ee/assets/Databases.md)
- [Identity providers](e2ee/assets/Identity-providers.md)
- [Web applications](e2ee/assets/Web-applications.md)
  
### Attack vectors

- [Vulnerable endpoints](e2ee/attack-vectors/Vulnerable-endpoints.md)
- [Unencrypted metadata](e2ee/attack-vectors/Unencrypted-metadata.md)
- [Unencrypted backups](e2ee/attack-vectors/Unencrypted-backups.md)
- [Insecure encryption algorithms](e2ee/attack-vectors/Insecure-encryption-algorithms.md)
- [Backdoors](e2ee/attack-vectors/Backdoor.md)
- [Ghost protocols](e2ee/attack-vectors/Ghost-protocols.md)
  
### Attacks

- [Chosen plaintext attack](e2ee/attacks/Chosen-plaintext-attack.md)
- [Impersonation attack](e2ee/attacks/Impersonation-attack.md)
- [Chosen ciphertext attack](e2ee/attacks/Chosen-ciphertext-attack.md)
- [Forgery attack](e2ee/attacks/Forgery-attack.md)
- [Replay attack](e2ee/attacks/Replay-attack.md)
- [Side-channel attack](e2ee/attacks/Side-channel-attack.md)
- [MitM client-to-server HTTPS attack](e2ee/attacks/MitM-client-to-server-HTTPS-attack.md)
- [MitM server-to-server HTTPS attack](e2ee/attacks/MitM-server-to-server-HTTPS-attack.md)
  
### Threats

- [Plaintext leaks](e2ee/threats/Plaintext-leaks.md)
- [Data tampering](e2ee/threats/Data-tampering.md)
- [Changed message order and delivery](e2ee/threats/Changed-message-order-and-delivery.md)
- [Public keyring identities leakage](e2ee/threats/Public-keyring-identities-leakage.md)
- [Automated verification](e2ee/threats/Automated-verification.md)
- [TLS/SSL PKI vulnerabilities](e2ee/threats/TLSSSL-PKI-vulnerabilities.md)
  
### Impacts

- [↑ Backdoors](e2ee/impacts/Backdoors.md)
- [↑ Usability issues](e2ee/impacts/Usability-issues.md)
