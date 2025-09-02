##  **1: Molecule Generation**

| Component  | Description                                                                              |
| ---------- | ---------------------------------------------------------------------------------------- |
| **Input**  | - Random latent vector (noise) of SMILES seed |
| **Model**  | -  LSTM - Trained on SMILES from ChEMBL                  |
| **Output** | - Novel molecule SMILES string(s) like `CC1=CC=CC=C1`                                    |
| **Goal**   | Generate **unique, valid, diverse** molecules that haven't been seen before              |
