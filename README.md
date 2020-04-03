# Exploratory Data Analysis of ALS Patient Data
### A Case-Study of Cognitive Data from a Patient with Amyotrophic Lateral Sclerosis
---
In the Git Repository I present the following files:
- **Data_exploration.ipynb** - Main analysis file that contains data preprocessing, visualization, annotation and analysis results.
- **EEG_Class.ipynb** - Main file with helper functions for data preprocessing and plotting.
- **Labelling_helper.ipynb** - Helper file for annotation (if the presented annotation UI cannot be used for whatever reason).
- **Auditory_Stimulation.ipynb** - Intermediary analysis results for testing if the setup for experiment 2 will yield sufficient amounts of data.
- **Report** - Writeup that presents a Literature review, Methodology, description of the Analysis and Results.

These notebooks demonstrate all data analysis performed for the Capstone Research Project by Michelle Hackl, in collaboration with the University of Vienna, Neuroinformatics Department under Prof. Moritz Grosse-Wentrup. Please only read the code notebooks in conjunction with the writeup, presented alongside them.

For data protection reasons, the patient data is not provided alongside this notebook. For access to the replication data, please contact the author under the following email: michelle.hackl@minerva.kgi.edu. We support replicable research and if you find issue with the analysis, please inform the author about it.

---
#### Abstract
In this project I present a concise overview of past attempts at brain-computer interface (BCI) communication with ALS patients and some of the hypotheses about why they have been unsuccessful to date. My project is an exploratory data analysis of 86 hours of current EEG data collected from a CLIS (completely locked-in state) ALS patient. The analysis is aimed at extracting cognitive activity in different frequency bands and observing their change over time. The goal of this is to identify cognitive measures that are stable enough to facilitate the identification of "high interest/high alertness" periods during which BCI communication with the patient is more likely to succeed. The preliminary results of the data analysis are presented and a follow-up experiment (currently in progress) is described.
