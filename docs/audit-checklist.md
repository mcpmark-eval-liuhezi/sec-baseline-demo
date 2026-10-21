# Security Audit Checklist

This checklist is used during the security-readiness workshop. Each section maps to one of the five standard security functions: **Identify, Protect, Detect, Respond, and Recover**.

## 1. Identify

- [ ] Inventory all repositories, packages, and deployments in scope
- [ ] Confirm asset ownership and responsible contacts for every system
- [ ] Document compliance requirements applicable to the environment

## 2. Protect

- [ ] Verify branch protection rules on the default branch
- [ ] Review least-privilege access for all collaborators and tokens
- [ ] Confirm secrets are stored in a secrets manager and not in code

## 3. Detect

- [ ] Enable and review secret scanning alerts
- [ ] Confirm Dependabot or code-scanning alerts are reviewed weekly
- [ ] Verify audit log and notification routing is enabled

## 4. Respond

- [ ] Confirm an on-call rotation and escalation path exists
- [ ] Document the incident response process for leaked credentials
- [ ] Run a tabletop exercise for a simulated compromised token

## 5. Recover

- [ ] Verify backups exist and a restore has been tested
- [ ] Document recovery time objectives and owners
- [ ] Confirm post-incident review steps and lessons-learned capture
