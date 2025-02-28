
Whenever I start a new project, aku tak start dengan coding right away—kena set up proper documentation dulu! I use a structured document workflow based on the Software Development Life Cycle (SDLC). 

Bila code dengan ai ( cursor in this case ) context tu sangat penting & lepas multiple tool calls agent ai tu akan hilang context. Sebab tu pentingnya ada docs ni untuk AI referral. 

Tapi yang paling pentingnya, dengan ada semua docs ni korang lagi faham apa yang korang bina.

Here's the prompt.


## 2. Required Documents



### 2.1 Analysis Phase (docs/2-analysis/)

- `requirements-specification.md`: Detailed functional and non-functional requirements

- `use-cases.md`: User interaction scenarios and flows

- `user-stories.md`: User stories with acceptance criteria

- `integration-requirements.md`: Third-party integration specifications



### 2.2 Design Phase (docs/3-design/)

- `system-architecture.md`: System components, data flow, and infrastructure

- `database-design.md`: Schema design, indexes, and data models

- `threat-model.md`: Security architecture and threat analysis

- `api-versioning-strategy.md`: API evolution and compatibility

- `encryption-key-management.md`: Key hierarchy and rotation policies



### 2.3 Development Phase (docs/4-development/)

- `version-control.md`: Git workflow and branching strategy

- `code-standards.md`: Coding guidelines and best practices



### 2.4 Testing Phase (docs/5-testing/)

- `test-plan.md`: Comprehensive test strategy

- `api-contract-testing.md`: Service integration testing



### 2.5 Deployment Phase (docs/6-deployment/)

- `deployment-guide.md`: Deployment procedures and configurations

- `operations-manual.md`: System operations and maintenance

- `production-checklist.md`: Pre-deployment verification list

- `disaster-recovery.md`: Recovery procedures and backup strategies

- `sla.md`: Service level agreements

- `incident-response.md`: Incident management procedures



## 3. Document Format Guidelines



For each document:

1. Use clear hierarchical structure (h1, h2, h3)

2. Include YAML/JSON examples for configurations

3. Add diagrams where applicable (using Mermaid or ASCII)

4. Provide code examples in appropriate languages

5. Use markdown tables for structured data

6. Include version control information



## 4. Content Requirements



Each document should include:

1. Clear purpose and scope

2. Detailed technical specifications

3. Implementation guidelines

4. Security considerations

5. Compliance requirements

6. Monitoring and metrics

7. Maintenance procedures



## 5. Special Instructions



1. Focus on security-first approach

2. Include compliance considerations (GDPR, SOC2, etc.)

3. Provide clear examples and code snippets

4. Add diagrams for complex flows

5. Include checklists for critical procedures

6. Cross-reference related documents



Please generate these documents following industry best practices and ensure they are interconnected and consistent with each other.



## 6. Document Generation Order



1. Start with requirements and analysis documents

2. Move to design documents

3. Create development guidelines

4. Establish testing framework

5. Finally, create deployment and operations documents



Each document should be practical, actionable, and maintainable.