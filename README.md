# model-checking-toolkit

This repository is for ACSOS 2025 submission paper; "A Run-time Verification Toolkit for Self-adaptive Systems Supporting Dynamic Model Changes".

This toolkit aims to implement run-time efficient model checking research, especially under unpredictable environmental changes that lead to updates of the system model.

This toolkit provides APIs below(from paper Fig.1):

<img width="1180" height="540" alt="スクリーンショット 2025-07-12 003235" src="https://github.com/user-attachments/assets/a6667ba0-fd4b-4002-8a4d-54fda412da4c" />


- Verification formula & cache generation
<img width="771" height="444" alt="スクリーンショット 2025-07-12 004219" src="https://github.com/user-attachments/assets/e8803db5-f798-4d45-a656-0a275ca34502" />

The toolkit performs necessary preprocessing based on the given system model and system requirement at design-time.

- Run-time verification

<img width="432" height="318" alt="スクリーンショット 2025-07-12 004317" src="https://github.com/user-attachments/assets/c6ff2017-bc1a-4e1b-9ce4-b91ec7c6f88b" />

The toolkit performs dynamic verification by sub-stituting observed parameter variable values to a verification formula at run-time.

- Re-generation of verification formulae (at run-time)

<img width="737" height="368" alt="スクリーンショット 2025-07-12 004422" src="https://github.com/user-attachments/assets/cc2e239a-bde8-484e-82a1-fe05bb78bcbe" />

The toolkit regenerates the verification formula based on the given changed system model at run-time.

For further instructions, please refer to the demonstration video link included in my paper.

# License
This project includes the following libraries:
- JUnit 5 : Eclipse Public License 2.0 (EPL-2.0)
- jama : Eclipse Public License (EPL) 1.0
- JOL-core : Eclipse Public License (EPL) 2.0
- Java SE 21:Oracle Binary Code License Agreement
