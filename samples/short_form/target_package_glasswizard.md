# Target Package: GLASS WIZARD 

## Summary

GLASS WIZARD is a threat actor known for targeting organizations inline with China's strategic goals. GLASS WIZARD is known for using a wide variety of tools, moving from generic multi user tools like Poison and PlugX to unique, actor specific malware such as WINNTI & Hydraq. The actor has TTPs that indicate a high level of adaptablity and even a large organization.

| Alternative Name | Source    |
|:-----------------|:----------|
| AXIOM | Novetta |

## Tactics, Techniques, & Procedures

- Uses a tiered approach to malware, starting with commodity tools and saving custom capabilities for harder targets.
- Leverages common network admin tools to move using compromised credentials.
- Utilizes strategic compromises (such as stealing certificates) to enable future attacks.

## Tools

| Name   | Description | Notes |
|:-------|:------------|:------|
| Poison Ivy | Remote Access Trojan | Commodity kit. |
| PlugX | Remote Acess Trojan | Commodity kit. |
| Gh0st | Remote Access Trojan | |
| WINNTI | Remote Access Trojan | Closely held but shared. |
| Derusbi | Unknown | |
| Hydraq | Unknown | |
| HiKit | Server Side Remote Access Trojan | Specific to Axiom |
| Zox | Remote Access Trojan | Malware family, specific to Axiom |

## Victim Profile

- Human Intelligence Information Sources
- Technology Organizations
- Non-Governmental Organizations (NGOs)
- Strategic compromises to steal useful resources (e.g. Bit9 signing certificates) 

Based on 3rd party reporting.

## Related Actors

| Name         | Type       | Notes |
|:-------------|:-----------|:------|
| WINNTI | Actor Group | High levels of overlap, possibly closely related. |
| Elderwood | Actor Group | From Symantec reporting. |

## References

- http://www.novetta.com/wp-content/uploads/2014/11/Executive_Summary-Final_1.pdf 
