# Hemolytik: A Database of Hemolytic and Non-Hemolytic Peptides

Welcome to the official documentation for **Hemolytik**, a comprehensive, manually curated database of experimentally determined hemolytic and non-hemolytic peptides. Hemolytic activity is a critical measure of a peptide's toxicity toward mammalian red blood cells (erythrocytes) and is a major limiting factor in the clinical development of peptide-based therapeutics .

**Web Server:** [http://crdd.osdd.net/raghava/hemolytik/](http://crdd.osdd.net/raghava/hemolytik/) 

---

## Citation

Gautam, A., Chaudhary, K., Singh, S., Joshi, A., Anand, P., Tuknait, A., Mathur, D., Varshney, G. C., & Raghava, G. P. S. (2014).
**Hemolytik: a database of experimentally determined hemolytic and non-hemolytic peptides.**
*Nucleic Acids Research*, 42(D1), D444–D449.
[https://doi.org/10.1093/nar/gkt1008](https://doi.org/10.1093/nar/gkt1008)

---

## About the Platform

Hemolytik was developed to provide a centralized resource for researchers studying antimicrobial peptides (AMPs), cell-penetrating peptides (CPPs), and other bioactive peptides. While many peptides demonstrate high therapeutic potential against pathogens or cancer cells, their application is often hindered by high hemolytic potency. This database facilitates the identification and design of peptides that maintain efficacy while minimizing toxicity to host cells.

The data is compiled from:
* **Published Literature**: Extensive manual curation of research articles.
* **Bioinformatics Databases**: Integration of data from the Antimicrobial Peptide Database (APD), Collection of Antimicrobial Peptides (CAMP), Dragon Antimicrobial Peptide Database (DAMPD), and Swiss-Prot.

---

## Key Features

### Database Content
* **Extensive Repository**: Contains approximately 3000 entries, including ~2000 unique peptide sequences.
* **Diverse Erythrocyte Sources**: Features hemolytic data evaluated against erythrocytes from 17 different sources, such as human, rat, sheep, and rabbit.
* **Comprehensive Annotations**: Provides details on peptide name, sequence, origin, reported function, chirality, and chemical modifications (e.g., C-terminal amidation, N-terminal acetylation).

---

## Technical Overview

The database is implemented using an Apache HTTP server with MySQL for data management and PHP/Perl for the web interface. Hemolytik utilizes structural and chemical descriptors to allow for in-depth comparative studies.

| Field | Description |
| :--- | :--- |
| **Peptide Info** | Name, sequence, length, and origin |
| **Hemolytic Data** | Percentage hemolysis, hemolytic concentration (e.g., $HC_{50}$), and erythrocyte source |
| **Experimental Info** | Assay type and concentration tested  |
| **Peptide Properties** | Chirality and N/C terminal modifications |

---

## Applications

* **Therapeutic Development**: Assisting in the optimization of peptides for human use by identifying non-toxic variants .
* **Predictive Modeling**: Providing high-quality datasets for training machine-learning algorithms to predict peptide hemotoxicity.
* **Comparative Toxicology**: Studying the differential sensitivity of erythrocytes from various species to peptide-induced lysis.

---

## Contact & Authors

**Prof. G.P.S. Raghava** Head, Department of Computational Biology
Indraprastha Institute of Information Technology (IIIT-Delhi), India.
**Email**: raghava@iiitd.ac.in 

---

## License

This resource is open-access and distributed under the terms of the **Creative Commons Attribution License**, permitting unrestricted use and distribution provided the original work is properly credited.
