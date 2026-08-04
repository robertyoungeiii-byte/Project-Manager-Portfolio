# Risk Register — EHR System Rollout

> **Note:** This is a fictional case study created to demonstrate technical 
> project management skills. It is not based on a real employer, client, 
> or project.

| ID | Risk Description | Category | Likelihood | Impact | Risk Score | Mitigation Strategy | Owner | Status |
|----|-------------------|----------|:---:|:---:|:---:|---------------------|-------|--------|
| R1 | Data migration errors corrupt or lose patient records | Technical | Medium | High | High | Run parallel systems during transition; full data validation pass before legacy system decommission | IT Director | Mitigated |
| R2 | Clinical staff resist adoption, reverting to workarounds | Organizational | High | High | High | Early hands-on training; embed "super users" at each site for peer support | Project Manager | Ongoing |
| R3 | HIPAA compliance gap during data migration | Compliance | Low | Critical | High | Compliance officer sign-off at each migration checkpoint; encrypted data transfer protocols | Compliance Officer | Mitigated |
| R4 | Regulatory deadline missed | Schedule | Medium | Critical | High | Build 3-week buffer into final site go-live; weekly steering committee check-ins | Project Manager | Ongoing |
| R5 | Vendor implementation team delays configuration | Vendor | Medium | Medium | Medium | Contractual SLAs with penalty clauses; weekly vendor sync calls | Project Manager | Ongoing |
| R6 | Patient care disruption during cutover window | Operational | Medium | Critical | High | Schedule cutover during lowest-patient-volume hours; maintain paper backup protocol for 48 hours | Clinic Site Directors | Mitigated |
| R7 | IT staff bandwidth insufficient across 6 sites | Resource | High | Medium | Medium | Stagger rollout schedule so IT support isn't split across simultaneous go-lives | IT Director | Ongoing |
| R8 | Billing system integration errors cause claim denials | Technical | Medium | High | High | Dedicated billing team testing phase before each site go-live; 2-week billing reconciliation window post-launch | IT Director | Mitigated |

## Risk Scoring Key
- **Likelihood:** Low / Medium / High
- **Impact:** Low / Medium / High / Critical
- **Risk Score:** Combination of likelihood × impact, used to prioritize mitigation effort

## Notes
- Risks R2 and R4 were treated as top priority throughout the project given 
  their high likelihood and organizational-wide impact
- Risk register was reviewed weekly during steering committee meetings and 
  updated as mitigation actions were completed

