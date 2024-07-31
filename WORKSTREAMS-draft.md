# CoSAI Workstreams -- DRAFT

## Purpose
This document lists milestones and deliverables for the initial three CoSAI workstreams. These workstreams are listed in the [CoSAI Charter](./CHARTER.md) and are exemplary of the type of work that project members would collaborate on with our partners across the industry and academia.

This document also lists additional workstream proposals which are still under review and might be promoted to full workstreams by a [full majority vote](https://www.oasis-open.org/policies-guidelines/oasis-defined-terms-2018-05-22#dFullMajority).

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
* Detection patterns for abusive inputs?

### AI Risk Governance 

Develop a risk and controls taxonomy, checklist, and scorecard to guide practitioners in readiness assessments, management, monitoring, and reporting of their AI products, services, and components. 

#### Proposed Deliverables, Milestones & In-scope Efforts
* Executive risk committee stakeholder recommendations (particularly around C-suite AI ownership)
* Suggest a tiered approach based on high, medium, low risks and corresponding controls. Map to evolving regulatory expectations.
* Tradeoffs of data control invariants and PETs [(link)](https://en.wikipedia.org/wiki/Privacy-enhancing_technologies) including Differential Privacy, TEEs / confidential computing, etc and the related impacts to model performance or other security and technical robustness properties
* Launch rubric or scorecard for evaluating organizational readiness for secure AI integration and use, based on the capability of the AI system


## Additional Workstream Proposals
The following workstream proposals are still under review.

### Securing AI Applications and Secure Integration Methodologies

Develop practices and solutions for securely integrating AI with existing processes through collective engagement on thought leadership, best practices, research, or building blocks. Effort will focus on patterns, approaches and methodologies for securing integrating AI model usage into classical applications and infrastructures. Workstream will build upon the AI Risk Governance and Software Supply Chain Security for AI systems workstreams. 

#### Questions and Comments
* David LaBianca: Do we start here? Is there a need for pre-work in the existing workstreams?
* David LaBianca: Other cross-organization collaborations we should highlight? 
* David LaBianca: One thing I like about this proposal is that it potentially allows us to more cleanly position our efforts as accretive to the different government-related regulatory / standards efforts… “Hey NIST - we are aligned and we are going to provide the ecosystem with easy to use patterns for spinning up <secure thing> in an AI environment… Our member orgs will then have impls for their cloud environments, sdks, models, etc”
* David LaBianca Opportunities to extend and / or leverage…
	* https://github.com/project-oak/oak
	* https://github.com/google/genc/blob/master/genc/docs/tutorials/tutorial_6_confidential_computing.ipynb
* Daniel Rohrer: How does an AI claim or CC claim tie together? How do you transit that through connected systems? 

#### Proposed Deliverables, Milestones & In-scope Efforts
* Collaboration and extension of efforts from other open efforts (e.g. CSA, etc), research institutions, NIST and similar organizations.
* Secure enclave and confidential computing for AI infrastructure patterns (on-device or server-based) – 
* How do “CC” Attestation claims integrate and chain to Model/Data and other claims.
* Zero Trust for AI Inference and Integration patterns covering Endpoints, Edge, Data Centers
* Use of PETs in AI Applications
