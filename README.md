# 🚀 Humanitarian Intelligence – Swiss AI Weeks Hackathon Challenge

Welcome to the **Humanitarian Intelligence** challenge, contributed by the [Swiss Agency for Development and Cooperation (SDC)](https://www.deza.eda.admin.ch/en) as part of the Swiss AI Weeks Hackathon.  

Your mission: **Prototype a multilingual AI assistant** that empowers international cooperation actors to access, compare, and learn from complex project data – instantly and meaningfully.  

---

## 🌍 Challenge Overview

**Problem Statement**  
International cooperation produces a wealth of information: project documents, evaluations, country programs, and strategic reports. Yet these insights often remain fragmented, hard to search, and underused.  

**Objective**  
Build a conversational interface that allows staff and partners to:  
- **Access** large volumes of SDC project and evaluation data.  
- **Compare** interventions across time, regions, and donors.  
- **Learn** from past projects to inform strategic decisions.  
- **Contextualize** SDC’s work by linking it with **global data sources** such as  
  - [OECD DAC](https://data-explorer.oecd.org/?fs[0]=Topic%2C1%7CDevelopment%23DEV%23%7COfficial%20Development%20Assistance%20%28ODA%29%23DEV_ODA%23&pg=0&fc=Topic&bp=true&snb=27) (official development finance statistics)  
  - [ReliefWeb](https://reliefweb.int) (humanitarian reporting)  
- **Reference** sources transparently in every answer.  
- **Communicate** in multiple languages (EN, FR, DE at minimum).  


> Smarter tools mean better decisions, faster responses, and greater impact for people in need.

---

## 📂 Repository Structure
```
.
├── data/
│ └── ActiveProjectPhases_SDC_250729.xlsx # General project info (title, description, outcomes, …)
│
├── links/
│ └── README.md # Link to public SDC documents (evaluations, cooperation programs, …)
│
└── README.md # You are here
```

- **data/** – Contains one Excel file with general project information extracted from the public [SDC project database](https://www.eda.admin.ch/deza/de/home/projekte/projekte.html).  
- **links/** – Link to centrally publicly available SDC documents and reports that can be used for retrieval and analysis.  

---

## 📊 Dataset Description

### ActiveProjectPhases_SDC_250729.xlsx
Each row represents a project financed by SDC. Key columns include:  
- `projectno` – Unique identifier
- `phase` – Phase number (SDC Projects have different phases)
- `title` – Project title
- `background` – Background/context in which project takes place
- `keyExpectedResults` – Main expected results of the project
- `lead` – Short description of the intervention  
- `outcomes` – Expected outcomes or objectives  
- `Region` – Geographical scope  
- `target` – Target (Group) 

### Linked Documents
In addition, you’ll find references to:  
- **Public evaluations 1960-2024** (impact assessments, learning reviews)  
- **All public SDC documents 2015-2025** (including country cooperation strategies, porject documentation, strategic frameworks, evaluations,...)  
- **Respective Metadata xml Files** Listing all files in the respective directory plus selected metadata (and identifiers)  

---

## 🔧 Suggested Features for Your Prototype

- Multilingual Q&A (EN/FR/DE minimum)  
- Comparison of SDC projects with other donors (e.g. OECD DAC, ReliefWeb data)  
- Transparent citations for every answer  
- Simple, intuitive UI for non-technical users  
- Modular, scalable ingestion pipeline (new projects/docs can be added easily)  

---

## 🧑‍🏫 Support for Hackers

You’ll have access to:  
- 📑 **Public SDC Documents 1960-2024**  
- 📊 **Excel datasets covering SDC projects**  
- 👩‍💻 **Mentoring from SDC experts** in international cooperation

---

## 🤝 About the Partner

The **Swiss Agency for Development and Cooperation (SDC)** is Switzerland’s agency for international cooperation. It works to alleviate suffering and poverty worldwide, promoting peace and security, and protecting the environment

SDC’s portfolio includes:  
- **Humanitarian aid** in natural disasters, crises, and conflicts  
- **Development cooperation** through bilateral and multilateral partnerships  
- **Global programs** addressing cross-cutting challenges such as climate change, health, and migration  

---

## 🚀 Why Hack?

International cooperation is under pressure – financially, logistically, and politically.  
By contributing to this challenge, you are **applying AI to real-world impact** with global relevance.  

> Smarter tools = better decisions = stronger cooperation = lives improved.  

---

## 📌 Next Steps

1. Explore the dataset in [`/data`](./data).  
2. Check additional resources in [`/links`](./links).  
3. Join the **Q&A session for hackers** (details from organizers).  
4. Start building your prototype!  

---

This respository is part of the Zurich hackathon of [Swiss {ai} Week](https://swiss-ai-weeks.ch/) happening on 26/27 September 2025.

By accessing or using the data provided, you agree to the following terms and conditions.

## Terms and Conditions
> The data is provided solely for the purpose of participating in the hackathon event held in Zurich, Switzerland, and for developing solutions directly related to the specific challenge you have selected. You are strictly prohibited from using the Data for any other purpose, including but not limited to:
> - Commercial use.
> - Research or development outside the scope of this hackathon challenge.
> - Personal use or any other unauthorized activities.
> 
> The data is provided "as is" without any warranties, express or implied, including but not limited to, warranties of merchantability, fitness for a particular purpose, or non-infringement. The hackathon organizers do not guarantee the accuracy, completeness, or reliability of the data.
>
> Immediately following the conclusion of the hackathon event, you are obligated to permanently and securely delete all copies of the data, including any derived or processed data, from all your devices, storage media, and systems. 

## Source of Data
The data of this respository has been provided by the [Swiss Agency for Development and Cooperation (SDC)](https://www.deza.eda.admin.ch/en) submitting the challenge.
