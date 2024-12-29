# SOuLMuSiC

**SOuLMuSiC** is a computational tool designed to predict the impact of all possible single-site amino acid substitutions on protein solubility, based on a combination of advanced computational techniques and biophysical insights.

---

## ✨ Features
- **Comprehensive Input Features**:
  - Biophysical properties of wild-type and mutated residues.
  - Energetic values calculated using various statistical potentials.
  - Mutational scores derived from protein language model approaches.
- **Shallow Artificial Neural Network**: Powered by a simple yet effective artificial neural network.
- **Reliable Predictions**: Provides the impact of mutations on protein solubility in an accurate and fasta way. 

---

## 📖 Content of this repository
This repository contains all the data utilized in our analysis but not the SOuLMuSiC code. If you want to run SOuLMuSiC visit our webserver http://babylone.3bio.ulb.ac.be/SOuLMuSiC/.   

* File PDB_D.zip: PDB structures of all the entries of dataset $\mathcal{D}$.
* File PDB_Dinv.zip: PDB structures of all the entries of dataset $\mathcal{D}_{inv}$.
* File 4ZFV.pdb: PDB structure of the entries of dataset $\mathcal{D}_{LGK}$.
* File 1IYT.pdb and 2NAO.pdb: PDB structures of the entries of the dataset $\mathcal{D}_{A\beta}$.
* File SOuLMuSiCDataset.csv: File with all mutations of $\mathcal{D}$ with proteins informations and literature reference. 
* File SOuL_dir.dat: File with experimental data and the SOuLMuSiC predictions of $\mathcal{D}$.
* File SOuL_inv.dat: File with experimental data and the SOuLMuSiC predictions of $\mathcal{D}_{inv}$.
* File LGK.dat: File with the experimental data and the SOuLMuSiC and PoPMuSiC predictions of $\mathcal{D}_{LGK}$. 
* File Abeta42.dat: File with the experimental data and the SOuLMuSiC predictions of $\mathcal{D}_{A\beta}$.
  
---

## 📝 Citation and Contact 📫
If you use **SOuLMuSiC**, please cite the following work:

> S. Attanasio, J. Kwasigroch, M. Rooman, and F. Pucci,  
> *Predicting protein solubility changes upon mutations: introducing SOuLMuSiC*, submitted.

SOuLMuSiC is free for academic users and is licensed for commercial use. For questions, feedback and information about commerical license, feel free to reach out to us via **Fabrizio.Pucci@ulb.be** or **Marianne.Rooman@ulb.be**.
