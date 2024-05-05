# Book1

## 6 Step Incident Response Process

1. **Preparation**
    - Prevent incidents by ensuring systems and networks are sufficiently secure.

2. **Identification & Scoping**
    - Triggered by an alert, event, or something found from threat hunting. This phase is used to better understand findings and scope the network for additional compromise.

3. **Containment Intelligence Development**
    - Contain the attack here, identify how attackers are maintaining persistence, communicating with C2, etc.

4. **Eradication/Remediation**
    - Once you've successfully identified and scoped out the extent of compromise, proceed to eradicate and remove any persistence from the malicious actors. If you did not compromise properly, they will be back. *Proper scoping is important.*

5. **Recovery**
    - Bring the company back to operation.
    - Examples include:
      - Improve Enterprise Authentication Model
      - Zero Trust policy
      - Rebuild compromised endpoints
      - Change systemwide user credentials

6. **Threat Intel Consumption**
    - Ensure the incident has been fully mitigated and follow-up countermeasures are done.

