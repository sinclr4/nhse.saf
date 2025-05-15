---
date: 2025-05-14T11:32:01+01:00
draft: false
title: "Framework Requirements" 
weight: 110 
--- 

### Strategic Alignment, Vision, and roadmap

|     | **Requirements** |
| --- | --- |
| S01 | The solution should be aligned to stated strategy approved at an executive level e.g. TD Design Authority, P&P DA etc. |
| S02 | We should be able to demonstrate which capabilities from the NHSE Business Capability Model the solution is realising, and any potential duplication identified |
| S03 | A well-formed and maintained product vision & roadmap should exist with appropriate detail around architecture elements |
| S04 | The solution design should be able to meet the stated user needs and overall business objectives/drivers |

### Decision Making & Governance

|     | **Requirements** |
| --- | --- |
| DM01 | Where a solution or part of solution is seen as tactical, short term or introduces / persist tech & architecture debt, remediations plans should be in place and agreed with the relevant stakeholders and governance groups.<br><br>Architecture Debt should be identified with implications, rationale and future mitigations plans (recorded in a Architecture Debt Register)<br><br>Plans should be realistic and funded. |
| DM02 | Spend control (GATS) and associated Government Digital Services & Service Design related guidance should be followed whilst developing the solution and be evidenced for service design & spend control reviews |
| DM03 | Architecture risks and issues should be managed effectively with the appropriate level of visibility and ownership |
| DM04 | There should be effective and commensurate stakeholder involvement with respects to solution design and architecture decisions. |
| DM05 | The solution design and architecture decisions should be managed effectively through local programme design authorities and TRG at the appropriate stages of the lifecycle.<br><br>The relevant Lead Architects and SMEs are engaged and are supportive |
| DM06 | The overall approach to architecture governance should be appropriate and commensurate with the nature of the solution |
| DM07 | All Architecture decisions should be documented with a lightweight Architecture Decision Record with options and clear rationale.<br><br>E.g. [software-engineering-quality-framework/any-decision-record-template.md at main · NHSDigital/software-engineering-quality-framework · GitHub](https://github.com/NHSDigital/software-engineering-quality-framework/blob/main/any-decision-record-template.md) |
| DM08 | All decision-making should be structured i.e. identify key strategic drivers, user need assess options against drivers, present rationale, clarity on trade-offs, dependencies, risks and issues understood etc.<br><br>&nbsp; |

### Solution Design & Methods

<table><tbody><tr><th></th><th><p><strong>Requirement</strong></p></th></tr><tr><td><p>SD01</p></td><td><p>An appropriate design methodology should<strong> </strong>be followed e.g. Domain Driven Design and should include NHS/CDDO Service Design and Secure By Design principles &amp; methods</p></td></tr><tr><td><p>SD02</p></td><td><p>The solution should be compliant with NHS England principles, policy, patterns and best practice</p></td></tr><tr><td><p>SD03</p></td><td><p>The solution should<strong> </strong>be compliant with relevant standards</p></td></tr><tr><td><p>SD04</p></td><td><p>Solution design should<strong> </strong>follow good practice design principles e.g.</p><ul><li>Separation of concerns</li><li>Encapsulation / Modularisation</li><li>Loose coupling</li><li>High cohesion / single responsibility</li><li>Design for flexibility/change</li><li>Etc.</li></ul></td></tr><tr><td><p>SD05</p></td><td><p>Solutions should<strong> </strong>focus on commodity products and services where possible/sensible.</p></td></tr><tr><td><p>SD06</p></td><td><p>An API First design methodology should<strong> </strong>be followed, where APIs are at the fore front of the design process, functionality and data is exposed via APIs and the needs of the API consumer have been considered.</p></td></tr><tr><td><p>SD07</p></td><td><p>We should<strong> </strong>treat internal (NHS England) and external consumers equally.</p></td></tr><tr><td><p>SD08</p></td><td><p>We should<strong> </strong>select the correct patterns for the use case, and any trade-offs justified and agreed.</p></td></tr><tr><td><p>SD09</p></td><td><p>We should<strong> </strong>adopt the right standards for API development, supported by user, consumer, and market / supplier engagement.</p></td></tr><tr><td><p>SD10</p></td><td><p>The API follows the lifecycle policy best practice as set out within <a href="https://nhsd-confluence.digital.nhs.uk/display/APM/Sunsetting+%28deprecation+and+retirement%29+phases">Sunsetting (deprecation and retirement)</a> policy</p><p>This should include any enforcement arrangements.</p></td></tr><tr><td><p>SD11</p></td><td><p>Solutions should<strong> </strong>adhere to (Aalto needs updating with full list)</p><ul><li>Government "Secure by Design" policy <a href="https://www.security.gov.uk/guidance/secure-by-design/">Link</a></li><li>NCSC CAF <a href="https://www.ncsc.gov.uk/collection/cyber-assessment-framework">Link</a></li><li>Access Control Guidelines <a href="https://www.ncsc.gov.uk/collection/cyber-assessment-framework/caf-objective-b/principle-b2-identity-and-access-control">Link</a></li><li>Policy - Strong Auth/MFA <a href="https://www.ncsc.gov.uk/guidance/authentication-methods-choosing-the-right-type">Link</a></li><li>Storage and Processing of Data Outside of the UK - Information Governance Policy <a href="https://digital.nhs.uk/data-and-information/looking-after-information/data-security-and-information-governance/nhs-and-social-care-data-off-shoring-and-the-use-of-public-cloud-services/guidance">Link</a></li><li>NHS England’s API strategy &amp; policy statements e.g. API Landscape policy document (<a href="https://aalto.digital.nhs.uk/#/document/viewer/b61e0f92-b168-4173-8344-353360f4250e?library=5464c07f-daf1-4eee-b9b6-22e6c4dfbbd0">Word - API Landscape policy v1.0 (digital.nhs.uk)</a></li></ul><p>(Note there are overlaps with the Engineering red lines, ensure a consistent response and do not repeat assessments)</p></td></tr><tr><td><p>SD12</p></td><td><p>The relevant cloud “Well Architected Frameworks” should<strong> </strong>be followed, and the solutions assessed against</p><p>(Note there are overlaps with the Engineering Software Quality Framework, ensure a consistent response and do not repeat assessments)</p></td></tr></tbody></table>

### Technology Choices

|     | **Requirements** |
| --- | --- |
| T1  | Technology choices should be made in line with the NHS England Technology Radar, corporate direction and wider industry trends using the associated processes to support decision making . [Tech Radar](https://radar.engineering.england.nhs.uk/index.html)<br><br>(Note there are overlaps with the Engineering red lines, ensure a consistent response and do not repeat assessments) |
| T2  | Technology choices should be appropriate to the problem and non-functional needs i.e. we are as equally aware of over engineering as we are to under engineering. |
| T3  | An appraisal should be made of any vendor lock considerations and associated risks, and these are understood and accepted/mitigated. |

### Non-Functional Profile

|     | **Requirement** |
| --- | --- |
| NF1 | Solutions should incorporate workload observability and understand service health |
| NF2 | Reliability & Resilience needs should be defined (in terms of standard NHS England service levels) and solution mechanisms to meet these needs are defined including metrics such as RTO, RPO etc. |
| NF3 | An overall volume and performance model should exist and includes business-realistic exceptional scenarios. |
| NF4 | Methods to measure sustainability to establish baseline and show improvement should be defined. |
| NF5 | Audit & logging requirements should be defined, and the solution can support them <https://www.ncsc.gov.uk/collection/device-security-guidance/managing-deployed-devices/logging-and-protective-monitoring><br><br><https://www.ncsc.gov.uk/collection/cloud/the-cloud-security-principles/principle-13-audit-information-and-alerting-for-customers> |
| **NF6** | **Disaster Recovery & Business Continuity** There should be clear requirements (commensurate with service levels) around DR & BC (and a pragmatic approach taken with regards DR/BC events planned for) Continuity plans and supporting documentation should reflect the requirements, technical & architecture constraints etc. |

### Re Use Principles and Development of Shared Services

|     | **Requirements** |
| --- | --- |
| RU1 | If reusing existing capabilities, we should have confidence that any additional functionality required can be sensibly and cost effectively added to the existing service i.e we are not bending something out of shape |
| RU2 | For new capabilities we should identify/recognise the potential re use opportunities which may drive design decisions, benefits etc. |
| RU3 | We should reuse capabilities as defined below:- |

| **Capability** | **Re Use** |
| --- | --- |
| Cohorting | CaaS |
| Citizen Messaging | NHS Notify |
| Staff Messaging | GOV.Notify and nhs.connect |
| Application Messaging | MESH or alternative as required |
| Demographics/MPI | PDS |
| Eventing | MNS |
| API Management | NHSE API Management Platform (which uses Apigee underneath) |
| Identity | CIS2 Auth/NHS Mail SSO/NHS login |
| Logging & Monitoring | Splunk/Sentinel/Cribl/Grafana (tbc – pending ODIN) |
| Data Analytics | FDP/CDP/DPS - FDP First |
| Public facing web presence | NHS.uk |
| Patient Flags | Flags service |
| Organisational Data | ODS |

| **Shared Services** |     |
| --- |  --- |
| **Capability** | **Re Use** |
| Auditing | Standard Audit tools/PARS (when live) |
| Cyber Security Monitoring | CSOC |
| Service Management & Support | ServiceNow |

### Documentation

|     | **Requirements** |
| --- | --- |
|D01| All architecture documentation should be maintained (with supporting processes and change control) within the appropriate NHS England knowledge store(s) e.g. Aalto, SharePoint, Confluence|
|D02| Documentation should be published “open by default” and exceptions handled according to policy i.e. sensitivity etc|
|D03| The architecture documentation should be appropriate in scope and quality for the solution covering (but not exclusively) :- 
*   Architecture Vision
*   Architecture Roadmap
*   Layer Diagrams
*   Capability Model and Solution Mapping
*   Non functional requirements
*   Conceptual Architecture
*   Logical Architecture
*   Physical (including network, infrastructure etc.)
*   Solution Architecture Overview (SDO)
*   Key Architecture Decisions (KADs)
*   Data Models
*   Data Flows
*   API Specifications
*   Volume and Performance Models
*   Architecture Decision Records
*   Assumption, Risks, Issues and Dependencies
*   Cyber Assessment Framework compliance

