# ENISA Space Threat Landscape Dataset and Dashboard

This repository provides the dataset and an interactive dashboard accompanying the European Union Agency for Cybersecurity (ENISA) *Space Threat Landscape* report (ISBN: 978-92-9204-696-5, DOI: 10.2824/8841206), publicly released on 26 March 2025. These resources are designed to assist cybersecurity experts within the commercial space sector in identifying and mitigating potential threats and are provided as is.

The listed security controls were derived from a comprehensive review of EU regulations, international cybersecurity frameworks, space sector-specific cybersecurity profiles, best practice guides, countermeasure taxonomies, and national guidelines available during the drafting period. Specifically, the following sources were consulted:

* Directive (EU) 2022/2555 of the European Parliament and of the Council of 14 December 2022 on measures for a high common level of cybersecurity across the Union, amending Regulation (EU) No 910/2014 and Directive (EU) 2018/1972, and repealing Directive (EU) 2016/1148 (NIS 2 Directive). *Eur-Lex*.  [https://eur-lex.europa.eu/eli/dir/2022/2555/oj/eng](https://eur-lex.europa.eu/eli/dir/2022/2555/oj/eng)
* International Organisation for Standardisation. ISO/IEC 27001:2022 Information security, cybersecurity and privacy protection — Information security management systems — Requirements. *ISO*.  https://www.iso.org/standard/27001. [https://www.iso.org/standard/27001](https://www.iso.org/standard/27001) *Note: This ISO standard is available for purchase from the ISO website and is not freely accessible.*
* National Institute of Standards and Technology. The NIST Cybersecurity Framework (CSF) 2.0. *NIST*.  [https://www.nist.gov/cyberframework](https://www.nist.gov/cyberframework)
* Scholl M, Suloway T. Introduction to Cybersecurity for Commercial Satellite Operations. NIST IR 8270. *NIST*.  [https://csrc.nist.gov/pubs/ir/8270/final](https://csrc.nist.gov/pubs/ir/8270/final) 
* Bartock M, et al. Foundational PNT Profile: Applying the Cybersecurity Framework for the Responsible Use of Positioning, Navigation, and Timing (PNT) Services. NIST IR 8323 Rev. 1. *NIST*.  [https://csrc.nist.gov/pubs/ir/8323/r1/final](https://csrc.nist.gov/pubs/ir/8323/r1/final) 
* Lightman S, Suloway T, Brule J. Satellite Ground Segment - Applying the Cybersecurity Framework to Satellite Command and Control. NIST IR 8401. *NIST*.  [https://csrc.nist.gov/pubs/ir/8401/final](https://csrc.nist.gov/pubs/ir/8401/final)
* McCarthy J, et al. Cybersecurity Framework Profile for Hybrid Satellite Networks (HSN). NIST IR 8441. *NIST*.  [https://csrc.nist.gov/pubs/ir/8441/final](https://csrc.nist.gov/pubs/ir/8441/final)
* National Aeronautics and Space Administration. Space Security: Best Practice Guide (BPG). *NASA*.  [https://swehb.nasa.gov/display/SWEHBVD/7.22+-+Space+Security%3A+Best+Practices+Guide](https://swehb.nasa.gov/display/SWEHBVD/7.22+-+Space+Security%3A+Best+Practices+Guide)
* Aerospace Corporation. Space Attack Research & Tactic Analysis (SPARTA). SPARTA Countermeasures v1. *Aerospace Corporation*.  [https://sparta.aerospace.org/countermeasures/SPARTA](https://sparta.aerospace.org/countermeasures/SPARTA)
* Federal Office for Information Security (BSI). IT-Grundschutz Profile for Space Infrastructures: Minimum Protection for Satellites Covering their Entire Life Cycle. *BSI*.  [https://www.bsi.bund.de/SharedDocs/Downloads/EN/BSI/Grundschutz/profiles/Profile_Space-Infrastructures.html](https://www.bsi.bund.de/SharedDocs/Downloads/EN/BSI/Grundschutz/profiles/Profile_Space-Infrastructures.html)
* Federal Office for Information Security (BSI). Technical Guideline BSI TR-03184 Information Security for Space Systems - Part 1: Space segment. *BSI*.  [https://www.bsi.bund.de/SharedDocs/Downloads/EN/BSI/Publications/TechGuidelines/TR03184/BSI-TR-03184_part1.html?nn=916896](https://www.bsi.bund.de/SharedDocs/Downloads/EN/BSI/Publications/TechGuidelines/TR03184/BSI-TR-03184_part1.html?nn=916896)
* Ministry of Economy, Trade and Industry (METI). Cybersecurity Guidelines for Commercial Space Systems. *METI*.  [https://www.meti.go.jp/english/policy/safety_security/cybersecurity/index.html](https://www.meti.go.jp/english/policy/safety_security/cybersecurity/index.html)

It is noteworthy that the Commission work programme 2025 highlights the critical importance of space operations to our interconnected economy, particularly for innovative services like environmental and climate monitoring. To establish a robust EU framework for regulating the conduct of European space operators and to foster a stable, predictable, and competitive business environment, the European Commission plans to introduce a Space Act. This Act will also address the increasing challenges posed by space debris and the environmental impact of space activities, and aim to maximise the benefits of the space economy. (Communication from the Commission to the European Parliament, the Council, the European Economic and Social Committee and the Committee of The Regions, [https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:52025DC0045&qid=1739518522375](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:52025DC0045&qid=1739518522375 ))

## Dataset

The dataset is provided in an Excel format (`Control Framework.xlsx`) and expands upon the control appendix of the ENISA report. It offers three distinct views:

* **Control View:** Detailed information about each security control.
* **Threat View:** Mapping of controls to specific threat categories.
* **Lifecycle View:** Alignment of controls with phases of the satellite lifecycle.

This detailed breakdown allows users to analyze and understand the relationships between controls, threats, and the satellite lifecycle, enabling more informed security decisions.

## Dashboard

To facilitate analysis and provide actionable recommendations, an interactive Microsoft PowerBi dashboard is included. This visualization tool leverages a comprehensive analysis of **281 controls** from **13 prominent cybersecurity frameworks**.

Key features of the dashboard include:

* Visualization of control mappings to the satellite lifecycle phases.
* Filtering and search capabilities to quickly identify relevant controls.
* Interactive charts and graphs for data exploration.
* Clear and actionable recommendations based on the analysis.

The dashboard is designed to help experts:

* Identify critical controls for each phase of the satellite lifecycle.
* Understand the coverage of existing frameworks against identified threats.
* Identify security measures based on risk/threat and relevance.

## Usage

1.  **Download the Dataset:** Download `Control Framework.xlsx` to your local machine.
2.  **Download the Dashboard:** Download `Control Framework.pbix` to your local machine.
3.  **Open the Dashboard:** Open `Control Framework.pbix` using Microsoft's PowerBI application (either the free Power BI Desktop or the Power BI Services)
4.  **Explore and Analyze:** Use the dashboard's features to explore the data, filter controls, and generate reports.
5.  **Reference the ENISA Report:** For context and background information, refer to the official ENISA Space Threat Landscape report.

You can easily update/change the dataset and refresh the dashboard on your device to show the changes. Either create the folder C:\Space and store the xlsx file there or through PowerBI 'Data source settings' assign a new location for the dataset

## Contributing

Contributions and feedback are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. If you want to propose a new framework and accompanying mappings get in touch.

## Contact

For contacting the authors please use market@enisa.europa.eu
For media enquiries about this paper, please use press@enisa.europa.eu

## License

Licenced under CC-BY 4.0 “Unless otherwise noted, the reuse of this document is authorised under the Creative Commons Attribution 4.0 International (CC BY 4.0) licence ([https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)). This means that reuse is allowed, provided that appropriate credit is given and any changes are indicated”.

## Disclaimer

This dataset and dashboard are provided as is, for informational purposes only. 

This publication represents the views and interpretations of ENISA, unless stated otherwise. It does not endorse a regulatory obligation of ENISA or of ENISA bodies pursuant to the Regulation (EU) No 2019/881.
ENISA has the right to alter, update or remove the publication or any of its contents. It is intended for information purposes only and it must be accessible free of charge. All references to it or its use as a whole or partially must contain ENISA as its source. 
Third-party sources are quoted as appropriate. ENISA is not responsible or liable for the content of the external sources including external websites referenced in this publication.
Neither ENISA nor any person acting on its behalf is responsible for the use that might be made of the information contained in this publication.
ENISA maintains its intellectual property rights in relation to this publication. 
