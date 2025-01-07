# CoSAI Workstreams

_This document was approved by the PGB on 4 August 2024_

## Purpose
This document lists milestones and deliverables for the initial three CoSAI workstreams. These workstreams are listed in the [CoSAI Charter](./CHARTER.md) and are exemplary of the type of work that project members would collaborate on with our partners across the industry and academia.

### Software Supply Chain Security for AI systems
Significant efforts are ongoing to extend SSDF and SLSA principles to the security of AI development. Classical software SSDF and SLSA solutions provide the foundation for secure software development yet the individual organizations continue to face challenges integrating provenance solutions into their infrastructure and development practices including determining how to address changes in provenance proofs, shifts in publisher trust, etc... As the efforts to expand provenance controls into the AI domain advance, this CoSAI workstream will focus on lowering the barriers to AI provenance adoption and risk management.

For the purposes of this workstream, provenance has the meaning defined in NIST SP 800-53 Rev. 5, and does not include broader considerations such as copyright/IP. 

#### Proposed Deliverables & Milestones
* Guidance and best practices regarding the evaluation of model and data provenance statements
* Approaches for addressing model provider provenance risks as an organization integrates 3rd-party models
* Best practices for evaluating full AI application provenance including the classical software elements and the AI models
* Proposals for the inclusion of additional provenance data to enable high-efficacy model provenance evaluation, such as
	* who performed the training and which phase of training (e.g., pre-training, feature engineering, fine-tuning, prompt engineering, etc)
	* governance and oversight of the training processes
	* development lifecycle tampering controls and evidence
	* training environment controls
	* training data geography, geographical constraints on use, etc
* How do Data->Model->Generation claims connection/transit through elements like C2PA etc..

### Preparing Defenders for a Changing Cybersecurity Landscape
Develop a defender’s framework to identify needed investments to address the security impacts of AI use by business applications, attackers, and defenders as well as mitigations techniques and best practices. The Defender’s framework aims to scale investments and mitigation strategies with the emergence of pivotal offensive cybersecurity advancements in AI models.

#### Proposed Deliverables, Milestones & In-scope efforts
* Education around the coming wave of vulnerability discovery and agent-driven attacks (what does a threat intel feed on AI Attacks look like?  How does one get access to such a feed?)
* Recommendations for avoiding abuse of publicly accessible LLMs from being co-opted as intelligence in attacks
* Avoiding distillation attacks, especially from advanced attackers
* Coordinated Disclosure in AI Contexts (e.g. AI-ISAC possibilities, PSIRT leverage for AI product vuln, etc) – How to balance accelerating attackers, and informing defenders
* Education and guidance on how to build AI Red Teaming capabilities that are needed for developers of software and hardware for AI solutions as well as user of AI framework
* Definition of training corpus and materials required to support the development of AI agent(s) to support defenders , DCR: Access to compute for learning.
* Detection patterns for abusive inputs

### AI Risk Governance 
Develop a risk and controls taxonomy, checklist, and scorecard to guide practitioners in readiness assessments, management, monitoring, and reporting of their AI products, services, and components. 

#### Proposed Deliverables, Milestones & In-scope Efforts
* Executive risk committee stakeholder recommendations (particularly around C-suite AI ownership)
* Suggest a tiered approach based on high, medium, low risks and corresponding controls. Map to evolving regulatory expectations.
* Tradeoffs of data control invariants and PETs [(link)](https://en.wikipedia.org/wiki/Privacy-enhancing_technologies) including Differential Privacy, TEEs / confidential computing, etc and the related impacts to model performance or other security and technical robustness properties
* Launch rubric or scorecard for evaluating organizational readiness for secure AI integration and use, based on the capability of the AI system

### Secure Design of Agentic Systems
Research and develop secure design patterns for AI-based agentic systems including updates to AI usage threat models, conceptual high-level secure design pattern(s), impacts to secure infrastructure design, and other agent integration and use based needs

#### Proposed Deliverables, Milestones & In-scope Efforts
* Develop a domain-specific scope covering key areas of investment, research, and need for agentic system security. Efforts will minimally include the following areas:
  * threat model updates
  * conceptual, high-level secure design patterns for agentic systems
  * research and development of secure identity patterns for agentic systems
* Develop an agentic-specific security threat model update in collaboration with other CoSAI workstreams
* Develop a conceptual secure design pattern for implementing / controling agentic systems
* Develop an secure agentic identity whitepaper covering the design approaches necessary for agentic identity usage
  

