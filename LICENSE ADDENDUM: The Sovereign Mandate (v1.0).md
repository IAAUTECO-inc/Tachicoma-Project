Project: Tachikoma / AEGIS Framework

Base License: Apache License 2.0

Effective Date: March 21, 2026

1. Purpose and Scope
This Addendum supplements the Apache License 2.0. It defines the Sovereign Mandate required for any industrial or institutional deployment of the Software. The goal is to ensure that the Software remains a "Digital Common" dedicated to human autonomy, physical safety, and European technological sovereignty.

2. The "Zero-Cloud" Mandate (Data Sovereignty)
Any deployment of the Software in a production environment involving sensitive human interaction (Assistive Robotics, Healthcare, Institutional Governance) must adhere to the following:

Local Inference: AI processing and decision-making logic must execute on local or sovereign edge infrastructure.

No Extraterritorial Telemetry: The Software shall not be configured to transmit raw biometric, personal, or environmental data to third-party cloud providers outside of the user's direct jurisdictional control.

3. Deterministic Accountability (Auditability)
To comply with the EU AI Act (High-Risk Category) and the AEGIS Governance Framework, any modification to the core orchestration layer must:

Maintain a Traceability Matrix linking algorithmic decisions to human-redacted specifications (Cahier des Charges).

Preserve the Hardened Kernel Isolation (e.g., FreeBSD Jails/Capsicum) to prevent lateral movement and unauthorized privilege escalation.

4. Ethical Use in Social AI & Robotics
The Software is specifically engineered to enhance the autonomy of people with disabilities. Any use of the Software to develop systems for mass surveillance, social scoring, or unauthorized kinetic intervention is strictly contrary to the IA_AUT_ECO Doctrine.

5. Transparency and Supply Chain (OpenChain)
Recipients and contributors are encouraged to:

Maintain a valid SBOM (Software Bill of Materials) in CycloneDX or SPDX format.

Provide a Rollback Protocol ensuring that the system can be restored to its "Primary Sovereign State" in case of architectural regression or security compromise.

6. Disclaimer of Commercial Influence
The Software's development is guided by technical performance and public interest. No commercial entity shall influence the "Layer 0" security primitives in a way that creates proprietary lock-in or hidden dependencies.

How to apply this Addendum:
Include this file in the root directory of your repository and add the following line to your README.md:

"This project is licensed under the Apache License 2.0, supplemented by the Sovereign Mandate Addendum to ensure long-term resilience and ethical autonomy."
