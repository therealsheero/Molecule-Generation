##  **1: Molecule Generation**

| Component  | Description                                                                              |
| ---------- | ---------------------------------------------------------------------------------------- |
| **Input**  | - Random latent vector (noise) or SMILES seed <br> - (Optional) Target protein embedding |
| **Model**  | - VAE / Diffusion Model / RNN <br> - Trained on SMILES from ZINC/ChEMBL                  |
| **Output** | - Novel molecule SMILES string(s) like `CC1=CC=CC=C1`                                    |
| **Goal**   | Generate **unique, valid, diverse** molecules that haven't been seen before              |
