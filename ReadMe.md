# Network Intelligence for Counterterrorism: A 9/11 Case Study

**Author**: Esosa Orumwese

## Project Overview

This project explores the network structure of the 9/11 terrorist group using graph analysis techniques. It aims to identify key players and relationships within the network to provide insights into the network’s resilience and potential vulnerabilities. The analysis demonstrates how network intelligence can be leveraged in counterterrorism efforts.

## Data Sources

1. **9/11 Terrorist Network Data (Full Network)**: 
   - Contains the complete network of the 9/11 attackers post-incident, detailing connections among members.
   - Data Source: [SNAP's GitHub](https://github.com/maksim2042/SNABook/blob/master/chapter4)
   - Files: 
     - `9_11_edgelist.txt`: Edge list representing connections among the network members.
     - `9_11_attrib.txt`: Node attributes including roles, nationalities, and other relevant information.

2. **Prior Contacts Network Data**:
   - Represents connections among the hijackers based on information available before the 9/11 attacks.
   - Data Source: [UCINET](https://sites.google.com/site/ucinetsoftware/datasets/covert-networks/911-hijackers)
   - Files:
     - `9_11_HIJACKERS_PRIORCONTACTS.csv`: Network data showing pre-incident interactions.
     - `9_11_HIJACKERS_edited_ATTR.csv`: Node attributes with manually added weights based on Lindelauf et al., 2011.

## Libraries Used

- **NetworkX**: For creating, analyzing, and visualizing complex networks.
- **Matplotlib**: For plotting and visualizing data.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.

## Key Insights

- The project highlights the structural vulnerabilities of the 9/11 network using metrics such as degree centrality, betweenness centrality, and clustering coefficients.
- Key figures in the network are identified, demonstrating the impact of potential interdictions on overall network stability.
- The comparative analysis between the full network and prior contacts network underscores how missing or overlooked connections could have impacted intelligence efforts.

## How to Use

1. Clone the repository and ensure the data files are correctly placed in the `./data` folder.
2. The code primarily focuses on data preparation, visualization, and analysis of network properties. Ensure all required libraries are installed (`NetworkX`, `Matplotlib`, `Pandas`, `NumPy`).
3. The full code can be found in `ECMM447_coursework_workspace.ipynb` notebook, while the approach and methodology are detailed in the attached project report.

## Future Work

- Expanding the analysis to include dynamic network changes over time.
- Incorporating machine learning algorithms to predict potential key players in covert networks.
- Extending the approach to other case studies in counterterrorism.

## Acknowledgments

- This project is based on the dataset available from SNAP and UCINET, along with manual additions based on prior research.
- Special thanks to the University of Exeter for the resources and support provided during this research.