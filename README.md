# PROJECT Apollo – Text and Network Analysis in Astronomy and Astrophysics

Supervised by Charles J. Gomez, this repository showcases the innovative PROJECT Apollo, aiming to uncover historical trends and collaborative networks within Astronomy and Astrophysics through advanced data analytics.

## Project Description
PROJECT Apollo aims to unveil historical trends in research works within Astronomy and Astrophysics by studying patterns and ways in which information and collaboration are shared 
internationally. Employing Natural Language Processing (NLP) algorithms and conducting Network Analysis on a vast dataset, this pioneering approach stands out, especially in terms of 
topic modeling and citation network analysis within the Astronomy field. To briefly explain the project, it can be divided into three overarching tasks, each comprising specific sub-tasks. The first task involves implementing topic modeling on a dataset of over 500,000 research abstracts dating back to 1824 (we have updated our dataset), using the recently developed Structural Topic Modeling algorithm, which surpasses the traditional Latent Dirichlet Allocation (LDA) model by integrating metadata for a more nuanced topic analysis. This task aims to identify the contributions of various countries to different topics within Astronomy and Astrophysics. We perform topic modeling dynamically, meaning we discover topics in different time intervals and then implement the Document Influence Model (DIM) to discover which of the topics in the later time intervals were influenced by topics in the preceding time interval. The second task focuses on identifying telescopes, satellites, and arrays used by countries for research, tackling the challenge of unlabeled data through a combination of manual labeling and a classification algorithm with weak supervision with ‘Snorkel’ framework. The third task involves performing Network Analysis to discover patterns of information flow and collaboration among countries and institutions, creating networks for citation, coauthorship (from the year 2000 onwards), and satellite data sharing. The project's novelty lies in its unique application of dynamic topic modeling and network analysis on citation, coauthorship, and satellite data collaboration networks in this field, marking a first in employing such methodologies.  

### Objectives
- Identify and analyze the contributions of different countries to the field over time.
- Decode the usage of astronomical tools such as telescopes and satellites in research.
- Understand the dynamics of information flow through citation and coauthorship networks.

## Novelty and Significance
As our goal is to study trends and patterns in international collaboration, Astronomy and Astrophysics have turned out the be the perfect fields for our study because they in particular are one of those unique fields where international collaboration is crucial when it comes to sharing of satellite and telescope technology, cosmic and celestial data, etc. The approach we take is novel because there is no other research that has implemented dynamic topic modeling in this field. We perform network analysis on citation network, co-authorship network and satellite data collaboration networks which is also the first of its kind. We then calculate deflated CitaDon Disruption Index which is a novel approach to calculating CDI.

## Data Source
The comprehensive dataset includes:
- Over 500,000 abstracts from OpenAlex, enriched with metadata for robust analysis.
- Citation, Coauthorship, and Satellite Data Sharing Networks to map out scholarly interactions.

## Methodology
- **Topic Modeling:** Utilizing algorithms like STM, DTM, and DIM for thematic analysis.
- **Text Classification:** Implementing the Snorkel framework for data categorization.
- **Network Analysis:** Employing 'Networkx' and other Python and R libraries to visualize connections.

## Installation
[DO NOT CLONE WITHOUT PRIOR APPROVAL from the AUTHORS]
Clone this repository and install dependencies:
git clone https://github.com/Harshvardhan-Singh1/Project-Apollo
pip install -r requirements.txt


## Usage
Update the `config.py` with your API keys and run the scripts to perform the analysis.

## Data Ethics and Consent
We prioritize ethical data practices, ensuring transparency, privacy, and fairness in data handling and algorithmic application. All data has been ethically sourced with the appropriate consents and is intended for academic research.

## Team and Acknowledgments
This project is conducted by Harshvardhan Singh under the supervision of Charles J. Gomez. Contributions from other experts in the field will be invited and duly acknowledged.

For a more comprehensive breakdown of the project's methodology and the novelty of the approach, please refer to the detailed project documentation.

## Note
The latest files for this research is predominantly stored, shared and managed between the two authors in other platforms (HPC repositories and box folders), the files on gitHub are only to showcase the projects to others. The data files and the SQL queries to retrieve and format the data from OpenAlex database is removed from this repository (to protect our data integrity) and is stored in our personal HPC server repository, and our personal box folder. 

## License

Copyright (c) 2024 Harshvardhan Singh

All Rights Reserved.

No part of this project, PROJECT-Apollo, nor any of its contents or associated code, may be reproduced, copied, modified or adapted, without the prior written consent of the author, unless otherwise indicated for stand-alone materials. The lisence restrictions will change after our research is published.
