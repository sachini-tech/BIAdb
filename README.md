# BIAdb – Benzylisoquinoline Alkaloids Database

## Overview

BIAdb is a curated database of Benzylisoquinoline Alkaloids (BIAs), an important class of naturally occurring alkaloids known for their pharmacological and therapeutic properties. The database compiles chemical, structural, biological, and functional information related to BIA compounds from multiple public resources and literature sources.
webserver ; https://webs.iiitd.edu.in/raghava/biadb/
zenodo : https://doi.org/10.5281/zenodo.20068972

The project aims to support researchers working in:

* Drug discovery and development
* Natural product chemistry
* Bioinformatics
* Synthetic biology
* Medicinal chemistry

The database includes compounds such as:

* Morphine
* Codeine
* Berberine
* Noscapine
* Papaverine
* Apomorphine
* Tubocurarine

---

## Features

### 1. Comprehensive BIA Dataset

* 846 unique benzylisoquinoline alkaloids
* 2504 total curated records
* Information collected from:

  * PubChem
  * KEGG
  * KNApSAcK
  * Comparative Toxicogenomics Database (CTD)
  * Literature curation

### 2. Physicochemical Properties

Each entry contains:

* Molecular weight
* Exact mass
* Molecular formula
* XLogP
* TPSA
* H-bond donors/acceptors
* Rotatable bonds

### 3. Structural Information

* Canonical SMILES
* Isomeric SMILES
* SDF/MOL/PDB structure files
* 2D and 3D molecular visualization

### 4. Search and Browse Tools

* Keyword search
* Advanced search
* Structure similarity search
* Substructure search
* Exact structure search
* Superstructure search

### 5. Clustering and Analysis

Compounds are clustered using the LibraryMCS algorithm based on Maximum Common Substructure (MCS) analysis.

### 6. External Database Integration

Links are provided to:

* PubChem
* KEGG
* PubMed
* Drugpedia

---

## Database Statistics

| Data Source                | Number of Entries |
| -------------------------- | ----------------- |
| KEGG                       | 196               |
| CTD                        | 145               |
| PubChem                    | 171               |
| Literature Sources         | 334               |
| **Total Unique Compounds** | **846**           |

---

## Technology Stack

### Backend

* MySQL
* PHP
* Apache Server
* Linux (LAMP Stack)

### Frontend

* HTML
* CSS
* JavaScript

### Visualization Tools

* Jmol
* Java Molecular Editor (JME)
* JC Search Tool

---

## Database Fields

Each database entry includes:

1. Compound Name
2. PubChem ID
3. KEGG ID
4. Source
5. Compound Type
6. Function
7. Molecular Weight
8. Exact Mass
9. Molecular Formula
10. XLogP
11. TPSA
12. IUPAC Name
13. H-bond Donors
14. H-bond Acceptors
15. Rotatable Bonds
16. Canonical SMILES
17. Isomeric SMILES
18. Structure Files
19. PubMed Links
20. Drugpedia Links

---

## Workflow

1. Data collection from public databases and literature
2. Manual curation and validation
3. Physicochemical property extraction
4. Structural clustering using LibraryMCS
5. Database integration
6. Search and visualization interface deployment

---

## Applications

BIAdb can be used for:

* Drug discovery research
* Natural compound screening
* Structure similarity analysis
* Synthetic pathway studies
* Molecular property analysis
* Pharmacological studies

---

## Future Scope

Planned improvements include:

* Addition of biosynthetic pathway information
* Inclusion of synthetic intermediates
* Expansion of compound dataset
* Improved search and analytics tools
* Automated database updates

---

## Reference

Singla D, Sharma A, Kaur J, Panwar B, Raghava GPS.
“BIAdb: A curated database of benzylisoquinoline alkaloids.”
BMC Pharmacology, 2010, 10:4.
DOI: 10.1186/1471-2210-10-4

Source PDF: filecite turn file0

---

## Availability

Original database links mentioned in the publication:

* [http://crdd.osdd.net/raghava/biadb/](http://crdd.osdd.net/raghava/biadb/)
* http://crdd.osdd.net/raghava/biadb/str.php?id=1874&show=SHOW-3D

---
## Contact 
GPS Raghava
Email:- raghava@iiitd.ac.in
IIIT Delhi
## License

This project summary is based on an open-access publication distributed under the Creative Commons Attribution License.
