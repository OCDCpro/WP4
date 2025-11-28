# WP4 – Open-Source Process Design Kit (PDK)

---

## 1. Objectives
Work Package 4 (WP4) delivers the complete technical foundation for the Design Challenge by providing a fully functional open-source Process Design Kit (PDK) and a reproducible design environment.  
This includes:

- selecting and adapting an open-source PDK to the project requirements,  
- defining and implementing a suitable EDA toolchain,  
- developing a training design for onboarding and education,  
- deploying and maintaining a server-based design environment,  
- and creating a fully documented Docker image for local development.

WP4 ensures that all participants can execute a complete ASIC design flow — from simulation to tape-out — using consistent and reproducible open-source tools.

---

## 2. Initial Conditions and Dependencies
WP4 builds on inputs from prior work packages, including:

- the conceptual definition of the toolchain and workflow,  
- existing open-source PDKs (e.g., IHP SG13G2, SKY130, GF180) and open-source EDA tools,  
- project-wide requirements for security-by-design, usability, and maintainability.

These foundations define the technical constraints and expectations for the PDK and the overall toolchain.

---

## 3. Subtasks (UAP)

### UAP 4.1 – Toolchain Selection & Adaptation of the PDK
This subtask establishes the technical core of the design flow.

Key activities:

- selecting a suitable open-source EDA toolchain based on competition requirements,  
- adapting the existing PDK to the chosen toolchain,  
- implementing scripts to streamline and automate the design flow,  
- documenting the full design process from simulation to tape-out,  
- integrating security-related considerations and design constraints.

The resulting PDK becomes the standard environment for training, design, and tape-out preparation.

---

### UAP 4.2 – Development of a Training Design (PDK Training)
This subtask creates a practical, user-friendly training entry point.

Tasks include:

- developing a simple example design that demonstrates the essential features of the PDK and toolchain,  
- providing guided intermediate design results for each step of the flow,  
- integrating the training design into the overall user documentation,  
- preparing a fully verified, tape-out-ready reference design.

This ensures new users can quickly understand and navigate the design environment.

---

### UAP 4.3 – Setup of a Test Server Environment
This subtask deploys the server-based design and training environment.

Activities include:

- provisioning and configuring a dedicated test server,  
- installing the selected EDA tools and PDK components,  
- creating user accounts and access controls,  
- providing documented example designs on the server,  
- validating the server with test designs and user workflows.

The server provides a consistent and centrally maintained environment for all participants.

---

### UAP 4.4 – Operation & Maintenance of the Test Server
To ensure continuous usability throughout the project, this subtask handles the operational phase.

Tasks include:

- applying updates to all PDK modules, tool versions, and system components,  
- handling user questions and support requests,  
- identifying and fixing bugs discovered during training or test runs,  
- integrating improvements based on user feedback from test sessions.

This ensures reliability, consistency, and up-to-date tool support.

---

### UAP 4.5 – Creation, Testing & Documentation of a Docker Image
This subtask enables long-term local reproducibility beyond the server infrastructure.

Activities:

- documenting all relevant server configurations and workflows,  
- creating a reproducible Docker image containing the full toolchain and PDK,  
- validating the Docker environment across systems,  
- providing documentation for future participants and independent users.

This allows users to run the design flow locally and independently of central infrastructure.

---

## 4. Expected Results (Outputs)

- **Adapted PDK:** A fully documented open-source PDK tailored to the competition’s requirements.  
- **Training Design:** A verified, tape-out-ready example design with accompanying training documentation.  
- **Test Server:** A fully operational design environment including toolchain, documentation, and example projects.  
- **Docker Image:** A portable and reproducible design environment enabling local execution of the complete flow.

These outputs form the technical backbone of the Design Challenge.

---

## 5. Milestones

- **MS 4.1 (Month 12):** First version of the adapted PDK  
- **MS 4.2 (Month 18):** Prototype test server operational  
- **MS 4.3 (Month 36):** Final documentation and Docker image released  

---

## 6. Project Context
WP4 spans the entire period from Month 6 to Month 36 and integrates technical contributions from multiple partners in the project.  
It provides the necessary infrastructure to ensure accessibility, reproducibility, and usability for all participants of the Design Challenge.

