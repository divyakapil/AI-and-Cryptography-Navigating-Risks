# AI and Cryptography: Navigating the Risks

This project explores the intersection of Artificial Intelligence (AI) and Cryptography, focusing on the potential risks that AI poses to traditional encryption systems. It investigates how AI can be leveraged both to compromise cryptographic security (e.g., via cryptanalysis and side-channel attacks) and to enhance it through intelligent adaptation.

Project Overview

As artificial intelligence technologies continue to advance, they present novel threats to the field of cryptography; a domain traditionally responsible for secure communication and data protection. This project addresses those threats through research, experimentation, and practical implementation.

Key Objectives
- Analyze the negative impacts of AI on cryptography.
- Build a machine learning model that simulates network behavior under normal and attack scenarios.
- Implement adaptive encryption techniques based on real-time system analysis.
- Provide practical solutions to strengthen cryptographic security.

Research and Methodology
- Studied AI-enabled cryptanalysis and side-channel attacks using real-world case studies.
- Identified attack vectors where AI enhances the efficiency of breaking traditional encryption.
- Developed a custom dataset with 1,000 samples simulating normal and attack scenarios.
- Attributes: load: System workload, rate: Activity level, integrity_flag: 0 (normal), 1 (under attack)

Attack Criteria:
- load > 160 or rate > 15 ➝ Under Attack
- Else ➝ Normal Operation
