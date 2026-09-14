# Hi, I'm Hussain 👋

**PhD Candidate in Cryptography** at the University of Debrecen, and **Lead Java Instructor** at NIX Tech Budapest.

I design cryptographic primitives from algebraic structures, prove security bounds for them, and teach Java to the next generation of developers.

---

## 📄 Publications

- **Ahmad, H., & Hannusch, C.** (2025). *A Scalable Symmetric Cryptographic Scheme Based on Latin Square, Permutations, and Reed-Muller Codes for Resilient Encryption.* **Cryptography** 9(4), 70. [doi:10.3390/cryptography9040070](https://doi.org/10.3390/cryptography9040070)

- **Ahmad, H., & Hannusch, C.** (2023). *A New Keyed Hash Function Based on Latin Squares and Error-Correcting Codes to Authenticate Users in Smart Home Environments.* **C2SI 2023**, Springer LNCS 13874, 97–110. [doi:10.1007/978-3-031-33017-9_8](https://doi.org/10.1007/978-3-031-33017-9_8)

- *In preparation:* Structural hardening and security evaluation of a scalable Latin-square SPN with key-dependent S-boxes.

**ORCID:** [0000-0001-6959-8352](https://orcid.org/0000-0001-6959-8352)

---

## 🔬 Research

**Symmetric primitive design and cryptanalysis.** My work builds block ciphers and hash functions from Latin squares and error-correcting codes, then analyses how well they hold up against differential and linear attacks.

Current work on the RM-LS cipher includes:

- **Wide-trail diffusion layer.** Diagnosed a structural weakness in the original bit-level permutation (single-bit differences could cross it activating only one S-box per round) and replaced it with MDS circulant matrices over GF(2^m) plus a key-dependent digit permutation. Proved a lower bound of ⌊R/2⌋·B_min active S-boxes that holds for every key, extending to linear cryptanalysis via the MDS transpose property.

- **MILP active-S-box analysis.** Modelled the minimum active-S-box count as a mixed-integer linear program and solved ~700 proven-optimal instances on an HPC cluster (Gurobi + HiGHS cross-validation). Result: the required round count tracks the code dimension *k*, not the Latin-square order *n*.

- **Key-schedule hardening.** Diagnosed a related-key weakness (5.8% key avalanche) and redesigned the schedule with round constants, butterfly rotations, and a logarithmic warm-up stage, reaching near-ideal SKAC statistics at zero steady-state cost.

- **S-box filtering.** An isotopism-filtering procedure guaranteeing per-key floors on differential probability and nonlinearity, certified as the attainability frontier of the additive Latin-square family.

**Post-quantum (ongoing).** Security and implementation analysis of the DHH cryptosystem, a McEliece variant over HL-codes.

**Earlier work.** Threshold secret sharing for multi-cloud storage (MSc thesis, CloudSim).

---

## 💻 Engineering

Java backend development and test automation, with production experience in banking systems.

- **Spring Boot / JPA / Hibernate / REST APIs** — the stack I build with and teach.
- **Test automation** — Selenium, REST Assured, JUnit.
- **Previously:** Financial Exchange Management System (1000+ users) and Insurance Record Management System (100,000+ records) at the Central Bank of Syria.

---

## 👨‍🏫 Teaching

Teaching is the part of my work I enjoy most.

- **NIX Tech Budapest** — Lead the Java track of Hungary's National Dual Training Program: 150+ students from 14 secondary technical schools over two years. Mentor 50+ developers and QA engineers transitioning into automation.
- **Graz University of Technology** — Guest lecturer, Data Management (SS2024).
- **University of Debrecen** — Teaching assistant, Logic in Computer Science and Foundations of Computer Security.

---

## 🛠️ Tools

| Domain | Tools |
| :--- | :--- |
| **Cryptography** | Python, NumPy, SageMath, Magma, GAP, Gurobi/HiGHS (MILP), NIST STS |
| **Engineering** | Java, Spring Boot, SQL, Docker, Azure, Git |

---

## 🌱 Currently exploring

Zero-knowledge proofs, secure multi-party computation, and formal security proofs.

---

## 📫 Contact

[LinkedIn](https://linkedin.com/in/7ussain-ahmad) · 7ussain.ahmad (at) gmail.com · [ORCID](https://orcid.org/0000-0001-6959-8352)
