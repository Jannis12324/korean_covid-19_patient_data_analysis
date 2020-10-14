# Date created
09.09.2020
# Project title
Korean Covid-19 patient data analysis.
# Description
This repository dives into the korean covid-19 patient data and extracts meaningful insights.
Find the related medium blogpost [here](https://medium.com/@jannis.j/recovery-and-death-of-korean-covid-19-patients-8b48fd25af74)
# Motivation
With the ongoing pandemic of Covid-19 I am analysing the bottleneck: The hospital stays and infections.
The notebook answers the three following questions:
1. How are the infections distributed amongst age and sex?
2. How long are the hospital stays per age and sex?
3. After how many days do the patients who do not recover die?

The questions are investigated with fitting charts and a detailed description is found in the blogpost.
# Data source
The data is originally from the [Korea Centers for Disease Control & Prevention](http://www.cdc.go.kr/).
The data used in this repository is from a [kaggle user group](https://www.kaggle.com/kimjihoo/coronavirusdataset)
called dataartist that aggregated the Korean government data from different regions.
and continuously improves the integrity
# Dependencies
matplotlib==3.3.2
numpy==1.19.2
pandas==1.1.2
pandas-profiling==2.9.0
seaborn==0.11.0
# Files
korean_covid-19_patients_data.ipynb - Jupyter notebook with the analysis
requirements.txt - Libraries needed to run the notebook
data - folder with csv files containing the raw Korean Covid-19 data
figures - folder containing the charts of the notebook as pngs for the blogpost

