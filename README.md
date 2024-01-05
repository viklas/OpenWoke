
## Overview
"OpenWoke" is an initiative focused on creating a standardised and transparent framework for organisations to declare their commitments and actions towards environmental sustainability, social responsibility, governance and publicly accountable position on historical and emerging social issues. It leverages modern technologies, including blockchain, to ensure transparency, accountability, authenticity and promote positive social impact.

## Vision
To empower organisations to be transparent about their impact and practices in key areas of corporate responsibility, and to provide a clear, standardised way for stakeholders to assess and recognise these efforts.

## OpenWoke v1 Specification

### YAML File Format
Organisations will create a YAML file as per the following structure to declare their commitments:

```yaml
openWoke:
  version: 1.0
  lastUpdated: YYYY-MM-DD
  organization:
    name: "<Organization Name>"
    website: "<Website URL>"
    industry: "<Industry>"
    headquarters: "<Headquarters Location>"
  commitments:
    environmentalSustainability:
      policyUrl: "<Policy URL>"
      kpis: 
        - description: "<KPI Description>"
          target: "<KPI Target>"
          currentStatus: "<Current Status>"
    socialResponsibility:
      policyUrl: "<Policy URL>"
      kpis: 
        - description: "<KPI Description>"
          target: "<KPI Target>"
          currentStatus: "<Current Status>"
    governance:
      transparencyReportUrl: "<Report URL>"
      kpis: 
        - description: "<KPI Description>"
          target: "<KPI Target>"
          currentStatus: "<Current Status>"
  certifications:
    - name: "<Certification Name>"
      awarded: "<Award Date>"
  blockchainRecord:
    transactionId: "<Blockchain Transaction ID>"
    validationStatus: "<Validation Status>"` 
```

### Key Components

-   **Environmental Sustainability**: Details on environmental policies, goals, and performance.
-   **Social Responsibility**: Information on initiatives in diversity, community engagement, and employee well-being.
-   **Governance**: Transparency and ethical governance practices.
-   **Certifications**: Recognitions and certifications received.
-   **Blockchain Record**: Immutable record of the OpenWoke declarations and validations, version controlled for updates.

### Peer-to-Peer Validation and Consensus

-   Utilizes blockchain technology for decentralized validation of the OpenWoke declarations.
-   A network of validators ensures the credibility of reported information.
-   Transparency through a public ledger that records all validations.

### Adoption and Implementation

Guidelines for organizations to adopt and implement the OpenWoke standard, including integrating blockchain validation and regularly updating their OpenWoke file.

## Getting Started

To adopt OpenWoke:

1.  Create your OpenWoke YAML file following the specified structure.
2.  Host the file on your organization's website and optionally as a DNS TXT record.
3.  Submit the file for P2P validation through the OpenWoke blockchain network.
4.  Regularly update your file to reflect current commitments and achievements.

## Contributing

We welcome contributions from individuals and organizations to enhance and evolve the OpenWoke standard. Please see our contribution guidelines for more information.

## License

OpenWoke is not yet licensed for re-use.
