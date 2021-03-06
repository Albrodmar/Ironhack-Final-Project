# Business to Business do not use demographics #
Final Project - Data Analytics Ironhack



## Clustering a B2B Client Database ##

On B2B besides the **direct commercial relationship**, valueable information can be obtained using VAT numbers.
- Current status of the company.
- Declared main activity of the company.
- Location.
- Company P&L.

This information could be helpful to:
Develop a look-alike process to obtain new clients
Find out accounts under/over-perfoming compared to their peers
Find out buying patterns in your B2B clients database 

### Technology Stack ###
SQL, python, pandas, selenium, matplotlib, UMAP, HDBSCAN

### Core ###
Extracting client’s buying history from the Company database. Classified every gsale on a product-category.
Through webscrapping  at [einforma.com](https://www.einforma.com/) enrich the dataset with valuable client information:
- Declared main activity
- Location Province
- Current operativity status 

Reduce the dataset with UMAP and proceed to clustering with HDBSCAN.

After the clustering, a csv file is generated with all the data that can be analyze using a Business Inteligent Software like [Power BI](https://powerbi.microsoft.com/es-es/) or [Tableau](https://www.tableau.com/). 

### Folder Structure ###
```bash 
└── project
    ├── .gitignore
    ├── requeriments.txt
    ├── README.md
    ├── notebooks
    │   ├── notebook1.ipynb
    │   └── notebook2.ipynb
    ├── final_data
    └── images
```
