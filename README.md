# Generative Metadata Format

This repository contains the JSON schema for the Generative Metadata Format.

The GMF standard can be used to store statistical metadata on tabular datasets, which can be used
to generate synthetic versions of the original dataset. By storing the statistical metadata information in
this intermediate standard, privacy can be ensured by careful manual disclosure control.

A Python reference implementation for generating GMF files and creating synthetic dataset is available on [GitHub](https://github.com/sodascience/metasynth).

The GMF standard is designed to be modular and extensible with more distributions and privacy enhancing mechanisms. Additional distributions might be available at a later date in this repository outside of the core directory.

# GMF format versions and metasyn versions

| GMF version | metasyn version compatibility |
| ----------- | ----------------------------- |
| 0.1         | metasyn < 0.4.0               |
| 0.2         | metasyn == 0.4.0              |
| 0.3         | metasyn == 0.5.0, 0.6.0       |
| 1.0         | metasyn >= 0.7.0, <= 1.0.3    |
| 1.1         | metasyn >= 1.1.0              |

<!-- CONTACT -->
## Contact
**Metasyn** (and the GMF schema attached to it) is a project by the [ODISSEI Social Data Science (SoDa)](https://odissei-data.nl/nl/soda/) team.
Do you have questions, suggestions, or remarks on the technical implementation? File an issue in the issue tracker or feel free to contact [Erik-Jan van Kesteren](https://github.com/vankesteren) or [Raoul Schram](https://github.com/qubixes).

<img src="soda.png" alt="SoDa logo" width="250px"/> 
