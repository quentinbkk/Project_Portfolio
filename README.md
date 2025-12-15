# Quentin's Portfolio

## Data Science & Machine Learning

### 1. AllFence: A database for any Fencing Federation looking to modernize their fencing data storage and presentation (competition schedules, player profiles)
  `summary`: AllFence is a centralized and interactive database designed to help emerging fencing federations modernize how they manage athlete information, competition results, and national rankings. Built with a structured relational schema and controlled vocabularies, the system improves transparency, data integrity, and accessibility for administrators, coaches, and the public.

  `code`: [https://github.com/quentinbkk/allfence/blob/main/PROJECT_STRUCTURE.md](https://github.com/quentinbkk/allfence)

  `prototype`: Accessible at https://allfence.vercel.app/

  `data`: Synthetic datasets for fencer profiles, competitions, rankings, and controlled vocabularies

  `outcomes`: The system implements a full database model (fencers, clubs, competitions, events, rankings), automatic ranking calculation, and a user-friendly interface for searching, updating, and viewing official fencing data (FRONTEND WIP). It provides a scalable, transparent foundation for supporting sport development and efficient federation operation

### 2. The Productivity Effects of Foreign Ownership in Laos - Undergraduate Dissertation; achieved First Class (Highest Honours)
  `summary`: I used panel data and econometric methods (fixed effects, IV, and matching) to estimate how foreign ownership affects firm productivity and to address endogeneity through multiple robustness checks.
  
  `code`: https://github.com/quentinbkk/Laos_Productivity/blob/main/B202054.do

  `final draft`: https://github.com/quentinbkk/Laos_Productivity/blob/main/Final%20Dissertation%20Quentin.pdf

  `data`: World Bank Enterprise Survey (https://www.enterprisesurveys.org/en/enterprisesurveys)

  `outcomes`: The analysis showed a consistent and statistically significant productivity premium for foreign-owned firms, even after addressing endogeneity with IV and matching approaches. It also highlighted how sensitive empirical results can be to model specification, reinforcing the importance of robustness checks in applied econometrics.
  
### 3. ShapeAI - A tool that generates a large synthetic dataset of basic geometric shapes and leverages this data to train to predictive models. 

  `summary`: I developed a classification system that recognizes what geometric shape a user draws on a notepad (circle, square, triangle, etc.), using a deep-learning model trained on a custom dataset of hand-drawn sketches. The system inputs the user’s drawing, processes it via a convolutional neural network, and outputs the predicted shape in real time, allowing seamless interactive recognition of sketches.

  `code`: https://github.com/quentinbkk/shapeAI  

  `data`: Custom collection of hand-drawn sketches across shape classes
  
  `outcomes`: The model achieved high accuracy in distinguishing basic shapes in interactive settings, enabling it to power a real-time drawing app that interprets free-hand sketches reliably.

### 4. Synthetic Spreadsheet Generator – Improving RAG Classification Accuracy for GridSense
  `summary`: I built a suite of Python scripts that generate synthetic spreadsheets across six different formats, designed to mimic real client data without exposing sensitive information. These datasets were used to fine-tune and evaluate our Retrieval-Augmented Generation (RAG) pipeline in GridSense, improving the model’s ability to correctly classify incoming spreadsheet types.

  `code`: https://github.com/quentinbkk/sheetgenerator

  `data`: Fully synthetic spreadsheets generated programmatically (no real client data).

  `outcomes`: The synthetic generators enabled large-scale testing and iterative refinement of the RAG classifier, significantly improving its accuracy and robustness while preserving data privacy.
  
### 5. Analysis of AMZN Stock Returns (2020-2025)

  `summary`: This project applies time-series econometrics to analyse Amazon’s stock using five years of daily data (2020–2025). The analysis investigates stylised facts of financial returns, tests market efficiency, builds volatility-forecasting models (ARMA/ARCH/GARCH), constructs an ex-ante 5-day forecast, performs Monte-Carlo simulations, and conducts an event study around Amazon’s 2021 CEO transition. It also includes a pairs-trading simulation using a cointegrated synthetic competitor stock.

  `code`: https://github.com/quentinbkk/Amazon-AFE-Project--First-Repository-/blob/main/amazonspyder.py

  `final draft`: https://github.com/quentinbkk/Amazon-AFE-Project--First-Repository-/blob/main/AFE%20Written%20Component.pdf

  `data`: Daily AMZN price data from Orbis; S&P500 returns for market-model estimation; simulated data for pairs-trading section.

  `outcomes`: The analysis found that Amazon’s stock returns exhibit classic financial time-series features—volatility clustering, heavy tails, and high persistence in volatility—best captured by a GARCH(1,1) model, with Monte-Carlo simulations confirming these dynamics. Tests supported the Efficient Market Hypothesis, the event study showed no significant abnormal returns around the 2021 CEO transition, and the pairs-trading exercise demonstrated cointegration with the synthetic comparator stock.
  
## WIP

### ML-Lib: A fully integrated ML library of classes and objects, made for me

### ContraBench: Research on latent contradictions in the processing of legal documents by language models

