# Personal CO2 Analysis
Data analysis project that aims to find out which lifestyle changes can reduce an individual's carbon footprint the most, using historical data on emissions by sector and per capita.

---

Climate change is an urgent global issue, but actionable personal guidance is often unclear, diffuse, or misleading. 
Additionally, it seems that the only genuine, long-term solution to climate change is systemic change, which is (for the most part) outside the control of average people. 

With this in mind... What changes can we make as individuals **today** to ensure that we're being responsible with the environment?

## Project Goal
Question: **What lifestyle changes can a single person make to reduce their CO2 emissions the most?**


### What this project covers
- Estimating the CO2 impact of individual actions and habits.
- Mapping personal behaviors to emitting sectors.
- Ranking high-impact lifestyle changes by potential CO2 reduction.
- Using historical data trends to support conclusions.

### What this project does **not** cover
- Greenhouse gases other than CO2.
- Other environmental indicators (e.g., water use, biodiversity, pollution outside CO2).
- Actions controlled mainly by governments/corporations and outside direct individual control.

### Analysis time range
To keep findings current and consistent, analyses use **2010–2023** unless otherwise specified.

## Notebook Roadmap
The project is organized as a sequence of notebooks:

1. **0. Introduction**  
   Project context, motivation, scope, and datasets.

2. **1. Base Knowledge**  
   Core concepts: greenhouse gases, what CO2 is, and why it matters.

3. **2. CO2 by Sector**  
   Sector-level emissions analysis and trend exploration.

4. **3. Personal Actions**  
   Mapping individual behaviors to sectors and estimating per-capita impact.

5. **4. Lifestyle Changes**  
   Identifying and ranking behavior changes with the largest potential reductions.

6. **5. Conclusion**  
   Final findings, visuals, and interpretation of personal impact in the bigger system.

## Structure
```text
personal-co2-analysis/
├── data/               # Datasets used in the analysis
│   ├── raw/            # Original datasets
│   └── processed/      # Cleaned and transformed datasets
│  
│       
├── notebooks/          # Analysis notebooks
│ 
├── references/         # BibteX files
│ 
├── LICENSE
└── README.md
