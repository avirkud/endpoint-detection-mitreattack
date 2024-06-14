# How does Endpoint Detection use the MITRE ATT&CK Framework?

This repository contains the code and data for the paper **How does Endpoint Detection use the MITRE ATT&CK Framework?** (USENIX Security 2024).

```
@inproceedings{virkud2024endpoint,
  title={How does Endpoint Detection use the MITRE ATT&CK Framework?},
  author={Apurva Virkud and Muhammad Adil Inam and Andy Riddle and Jason Liu and Gang Wang and Adam Bates},
  booktitle={USENIX Security Symposium},
  year={2024}
}
```

## Data
- *techniques.csv* enumerates the techniques and corresponding tactics from v11 of the MITRE ATT&CK Framework.
- *splunk_rules.csv*, *elastic_rules.csv*, and *sigma_rules.csv* are the data snapshots of the [Splunk](https://github.com/splunk/security_content/), [Elastic](https://github.com/elastic/detection-rules), and [Sigma](https://github.com/SigmaHQ/sigma) rulesets, taken in October 2022, that we use in this work. The original repositories for the three rulesets are open-source and available on GitHub at the links.
- *malpedia.txt* is a list of threats and software scraped from the [Malpedia library](https://malpedia.caad.fkie.fraunhofer.de/).
- *rulesets_software.csv*, *rulesets_groups.csv*, and *rulesets_campaigns.csv* contain the entity to rule index mappings. These entities are taken from the lists of common software, threat groups, and campaigns maintained by MITRE ATT&CK.
- *combined_rules_annotated_entities.csv* contains all rules tagged with the extracted keywords and additional annotations.

## Code
- *RQ1 Analysis.ipynb* contains the analysis for RQ1: How do products use ATT&CK?
- *RQ3 Analysis.ipynb* contains the analysis for RQ3: How consistently is ATT&CK applied?

## Citation

Please use the following citation (provided in [BibTex](www.bibtex.org/) format) for this repository:

```
@inproceedings{virkud2024endpoint,
  title={How does Endpoint Detection use the MITRE ATT&CK Framework?},
  author={Apurva Virkud and Muhammad Adil Inam and Andy Riddle and Jason Liu and Gang Wang and Adam Bates},
  booktitle={USENIX Security Symposium},
  year={2024}
}
```