# DS4320_Project1: Predicting California Wildfire Burn Area Using Causal, Temporal, and Weather Data

### Executive Summary
This README now documents a GFM-focused DS 4320 project and includes completed project metadata (name, NetID, DOI, links, and license) plus a summary table for quick reference. It also contains a defined problem statement, rationale, references with footnotes, a terminology table, callout examples, and code highlighting examples to demonstrate practical GitHub Flavored Markdown usage.

---
| Spec | Value |
|---|---|
| Name | Jessica Ni |
| NetID | dkh8my |
| DOI | [https://doi.org/10.1000/182](https://doi.org/10.1000/182) |
| Press Release | [edit this](https://) |
| Data | [link to data](https://doi.org/10.1000/182) |
| Pipeline | [analysis code](https://doi.org/10.1000/182) |
| License | [MIT](LICENSE.md) |

---

## Problem Definition
### General and Specific Problem
* **General Problem:** Predicting wildfire risk
* **Specific Problem:** Predicting wildfire size (acres burned) in California based on human activity, temporal factors, and weather conditions

### Rationale
The general problem of predicting wildfire risk is broad and encompasses many unknowns of where and what fires to focus on. To make the problem more focused and actionable, I refined it to specifically predict wildfire size (acres burned) in California based on human activity, temporal factors, and weather conditions. This refinement allows us to focus on specific, measurable factors that are known to influence wildfire size, such as temperature, wind speed, and human activities like campfires or smoking. By narrowing the scope to California, we can also focus on region-specific data for more accurate predictions instead of trying to generalize results across different regions with varying wildfire dynamics. This refined problem statement is more actionable as it provides a clear target variable (wildfire size) and specific predictors (human activity, temporal factors, and weather conditions) that can be used to develop a predictive model. 

### Motivation
According to the National Interagency Fire Center, the state of California leads the country with the most wildfires. Wildfires can cause significant damage to public areas, ecosystems, and human health. Predicting wildfire size can help authorities allocate resources more effectively, issue timely warnings to residents, and implement preventive measures to reduce the likelihood of wildfires. Overall, understanding the factors that contribute to wildfire size and being able to predict it can help inform public safety and mitigate any negative impacts of wildfires in the future.

### Press Release Headline and Link
[**edit this later!!!!**](https:)

## Domain Exposition
### Terminology


| Term | Definition |
|------|------------|
| Wildfire | An uncontrolled fire occurring in vegetation, often influenced by weather, human activity, and natural causes. |
| Wildfire Ignition Risk | The likelihood of a wildfire starting in a given area based on various factors such as weather conditions and human activity. |
| Burn Area | The area of land that has been affected by a wildfire, often measured in acres or hectares. |
| Causal Factors | Human or natural activities that can ignite or influence the spread of a wildfire (e.g., campfires, lightning, equipment use). |
| Temporal Factors | Time-related factors such as seasonality, time of day, and historical wildfire patterns that can influence wildfire ignition risk. |
| Weather Conditions | Environmental factors such as temperature, humidity, wind speed, and precipitation that can influence wildfire ignition risk. |
| Fire Weather Index | A numerical index that combines various weather factors to assess the potential for wildfire ignition and spread. |
| Predictive Model | A computational model that uses historical data to make predictions about future events, in this case, the size of wildfires. |
| California | A state in the United States that is particularly prone to wildfires due to its climate and vegetation. |

### Domain Explanation
This project lives in the domain of environmental science and public safety. On the environmental side, it focuses on understanding and predicting wildfire burn risk based on weather conditions, time factors, and human or nature related activity. The project involves utilizing historical wildfire incident data to understand the relationships between these factors and wildfire size, and then using this understanding to develop a predictive model that can inform residents and authorities about wildfire size risk in California. In the public safety domain, the project aims to provide actionable insights that can help guide preventive measures, resource allocation, and other public safety strategies to mitigate the impact of wildfires in California.

### Background Readings 
*Link to Github folder of PDFs:* ______

### Background Readings Table
| Title | Description | Direct Link | Link to File in Folder |
|-------|-------------|-------------|-------------------------|
| National Fire News | This website provides up-to-date information and statistics on wildfire incidents across the United States. It includes data on fire locations, sizes, and containment status. | [National Fire News](https://www.nifc.gov/fire-information/nfn) | [National Fire News](./Background%20Readings/National%20Fire%20News.pdf) |
| California Wildfire History & Statistics | This blogpost from Frontline Wildfire Defense provides a historical overview of wildfires in California, including statistics on California wildfire data measuring the impact that wildfires have on residents, structures, and the environment. It covers a few major wildfires in California history and provides lessons learned from those events. | [California Wildfire History & Statistics](https://www.frontlinewildfire.com/wildfire-news-and-resources/california-wildfires-history-statistics/) | [California Wildfire History & Statistics](./Background%20Readings/California%20Wildfire%20History%20and%20Statistics.pdf) |
| Recent advances in explainable Machine Learning models for wildfire prediction | This research highlights a machine learning model framework for wildfire forecasting and burned area estimation. It explores interactions between factors that contribute to model predictions and adopts a new method to show contributions of hyper-parameters on model learning. | [Recent advances in explainable Machine Learning models for wildfire prediction](https://www.sciencedirect.com/science/article/pii/S2590197425000485) | [Recent advances in explainable Machine Learning models for wildfire prediction](./Background%20Readings/Recent%20advances%20in%20explainable%20Machine%20Learning%20models%20for%20wildfire%20prediction.pdf) |
| How do Wildfires Start? | This article from Climate Check explains the various ways that wildfires can start, including natural causes like lightning and human activities such as campfires, fireworks, and outdoor burning. It also discusses the conditions that can contribute to wildfire ignition and spread. | [How do Wildfires Start?](https://climatecheck.com/risks/fire/how-do-wildfires-start) | [How do Wildfires Start?](./Background%20Readings/How%20do%20Wildfires%20Start.pdf) |
| Inference of Wildfire Causes From Their Physical, Biological, Social and Management Attributes | This research article explores machine learning approaches to analyze data and identify patterns that can help infer the causes of wildfires. It is based off the prevention of human-caused wildfires, which account for >60% of ignitions across western United States (WUS), as an effective way of reducing wildfire risk. | [Inference of Wildfire Causes From Their Physical, Biological, Social and Management Attributes](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2024EF005187) | [Inference of Wildfire Causes From Their Physical, Biological, Social and Management Attributes](./Background%20Readings/Inference%20of%20Wildfire%20Causes%20From%20Their%20Physical,%20Biological,%20Social%20and%20Management%20Attributes.pdf) |


## Data Creation
### Provenance
### Code
### Bias Identification
### Bias Mitigation
### Rationale for Critical Decisions

## Metadata
### Schema ERD
### Data Table
### Data Dictionary
### Data Dictionary Uncertainty Quantification