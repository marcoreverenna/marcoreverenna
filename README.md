<h1 align="left">It's-a me, Marco! 🇮🇹</h1>

<p align="left">
  <b>AI researcher & PhD student in computer science and biology</b><br/>
  Multi-omics Network Analysis (MoNA) group · Novo Nordisk Foundation Biotechnology Research Institute for the Green Transition (BRIGHT), Technical University of Denmark
</p>

<p align="left">
  <a href="https://www.linkedin.com/in/marco-reverenna-151787190/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:marcoreverenna@gmail.com"><img src="https://img.shields.io/badge/Email-marcoreverenna%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <!-- Add your IDs and uncomment:
  <a href="https://scholar.google.com/citations?user=YOUR_ID"><img src="https://img.shields.io/badge/Google%20Scholar-4285F4?style=flat&logo=googlescholar&logoColor=white" alt="Google Scholar"/></a>
  <a href="https://orcid.org/0000-0000-0000-0000"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=flat&logo=orcid&logoColor=white" alt="ORCID"/></a>
  -->
</p>

---

### About me

I build machine-learning methods and computational workflows for **proteomics**, with a focus on
**AI-driven de novo protein sequencing**: reconstructing full-length protein sequences, such as antibodies
and nanobodies, directly from mass-spectrometry data, without relying on reference databases.

**Research interests**
- 🧬 De novo peptide & protein sequencing from MS/MS data
- 🤖 Deep learning for biological sequences (transformers, foundation models, graph neural networks)
- 🕸️ Multi-omics data integration and network analysis
- ⚙️ Reproducible, scalable bioinformatics pipelines

**Currently working on**
-  A **Nextflow pipeline for de novo proteomics** that brings together multiple tools for de novo peptide sequencing and protein assembly in one reproducible workflow

---

### Research & projects

#### [Talk to your spectra: a command-line interface and Model Context Protocol server for agentic and manual peptide-spectrum-match inspection](https://github.com/UadKLab/proteomics-mcp)
![Coming soon](https://img.shields.io/badge/manuscript-coming%20soon-lightgrey)
[![GitHub](https://img.shields.io/badge/GitHub-proteomics--mcp-181717?logo=github)](https://github.com/UadKLab/proteomics-mcp)

A command-line tool and **Model Context Protocol (MCP) server** for inspecting peptide-spectrum matches.
It brings results from MaxQuant, FragPipe, Proteome Discoverer, InstaNovo and Casanovo into one shared schema,
predicts fragment intensities, scores matches and renders interactive spectra, so the same analysis can be
run by a person at the terminal or by an LLM agent.

<sub>Sugár S.N., Van Goey J., Nesterovich A., Houngue I.H.J., **Reverenna M.**, Francavilla C., Kalogeropoulos K. · *Manuscript coming soon*</sub><br/>
<sub>[Code](https://github.com/UadKLab/proteomics-mcp)</sub>

#### [Learning from tandem mass spectra at scale with a self-supervised foundation model for proteomics](https://doi.org/10.64898/2026.09.03.747733)
[![bioRxiv](https://img.shields.io/badge/bioRxiv-2026-B31B1B)](https://doi.org/10.64898/2026.09.03.747733)
![Co-first author](https://img.shields.io/badge/co--first%20author-2EA44F)

A transformer encoder pretrained to **reconstruct masked regions of tandem mass spectra**, learned from a corpus
of about 1.6 billion MS/MS spectra without using peptide sequences as supervision. Its embeddings capture
fragmentation method, instrument and post-translational modifications, and transfer to de novo sequencing,
database-free identification and run-level classification.

<sub>Nieuwoudt M., **Reverenna M.**, Patel D., Catzel R., Houngue I.H.J., Daniel J., Eloff K., Santos A., Lopez Carranza N., Jenkins T.P., Van Goey J., Kalogeropoulos K. · *bioRxiv* (2026)</sub><br/>
<sub>[Preprint](https://doi.org/10.64898/2026.09.03.747733) · [Embedding explorer](https://instadeepai.github.io/InstaNovo-FM)</sub>

#### [Generalizable direct protein sequencing with InstaNexus](https://doi.org/10.1016/j.mcpro.2026.101547)
[![MCP](https://img.shields.io/badge/Mol.%20Cell.%20Proteomics-2026-0B5394)](https://doi.org/10.1016/j.mcpro.2026.101547)
![First author](https://img.shields.io/badge/first%20author-2EA44F)
[![PyPI](https://img.shields.io/pypi/v/instanexus?color=blue)](https://pypi.org/project/instanexus/)

An end-to-end workflow for **direct protein sequencing**. It combines AI-driven de novo peptide sequencing
([InstaNovo](https://github.com/instadeepai/instanovo)) with tailored assembly, clustering, alignment and
consensus steps to reconstruct contiguous sequences of protein therapeutics such as antibodies and nanobodies.
A book chapter on InstaNexus is forthcoming with **Springer Nature**.

<sub>**Reverenna M.**, Wennekers Nielsen M., Wolff D.S., Daniel J., Lytra E., Thumtecho S., Colaianni P.D., Ljungars A., Laustsen A.H., Schoof E.M., Van Goey J., Jenkins T.P., Lukassen M.V., Santos A., Kalogeropoulos K. · *Molecular & Cellular Proteomics* 25(4), 101547 (2026)</sub><br/>
<sub>[Paper](https://doi.org/10.1016/j.mcpro.2026.101547) · [Preprint](https://doi.org/10.1101/2025.07.25.666861) · [Code](https://github.com/Multiomics-Analytics-Group/InstaNexus)</sub>
<!-- Add the Springer Nature chapter link here once available -->

#### Earlier work

#### [Human embryos with segmental aneuploidies display delayed early development](https://doi.org/10.1016/j.fertnstert.2024.10.042)
[![Fertil Steril](https://img.shields.io/badge/Fertil.%20Steril.-2025-6F42C1)](https://doi.org/10.1016/j.fertnstert.2024.10.042)

A multicenter time-lapse (morphokinetic) analysis showing that human embryos carrying segmental aneuploidies
develop more slowly during the earliest stages.

<sub>Figliuzzi M., Bori L., Ottolini C.S., Picchetta L., Caroselli S., **Reverenna M.**, Poli M., Campbell A., Smith R., Coticchio G., Cimadomo D., Rienzi L.F., Meseguer M., Capalbo A. · *Fertility and Sterility* 123(4), 624–633 (2025)</sub><br/>
<sub>[Paper](https://doi.org/10.1016/j.fertnstert.2024.10.042)</sub>

<!-- Template for further entries:
#### [Title](paper-link)
[![Venue](https://img.shields.io/badge/Venue-Year-555555)](paper-link)

One or two sentences on what the work does.

<sub>Author A., **Reverenna M.**, Author B. · *Journal* (Year)</sub><br/>
<sub>[Paper](link) · [Code](link)</sub>
-->

---

### Tech stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)

**Machine learning & data science**
![PyTorch Geometric](https://img.shields.io/badge/PyG-3C2179?style=flat&logo=pyg&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

**Bioinformatics & workflows**
![Snakemake](https://img.shields.io/badge/Snakemake-039475?style=flat&logo=snakemake&logoColor=white)
![Nextflow](https://img.shields.io/badge/Nextflow-0DC09D?style=flat&logo=nextflow&logoColor=white)
![MMseqs2](https://img.shields.io/badge/MMseqs2-555555?style=flat)
![Clustal Omega](https://img.shields.io/badge/Clustal%20Omega-555555?style=flat)

**Infrastructure**
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

---

<p align="left">
  💬 Always happy to collaborate and open to new projects, in proteomics, AI or any other field. If you have an interesting idea, feel free to reach out!
</p>
