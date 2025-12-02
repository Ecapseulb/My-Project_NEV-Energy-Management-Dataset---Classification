# NEV Energy Management Dataset

## Introduction

This notebook documents how we train models from a given dataset to predicting manufacturing defects. It includes EDA, models training and comparison.

**Models include:** **Support Vector Machine**, **Decision Tree**, **Random Forest**, **Extra Trees**, **AdaBoost**, **Gradient Boost**, **XGBoost**, **LightGBN** and **CatBoost**.

Also, we use the three best performing models above to do **Voting Classifier** and **Stacking Classifier**.

## About Dataset

**Introduction**

The NEV Energy Management Dataset is designed to support research on optimizing energy management strategies for New Energy Vehicles (NEVs) using Multi-Agent Reinforcement Learning (MARL). The dataset captures realistic driving conditions, power distribution, fuel consumption, and battery health across different driving cycles.


**Key Features**

- 1000 samples of vehicle energy consumption and management data.
- Covers standard driving cycles: WLTC (World Light Vehicle Test Cycle) and HWFET (Highway Fuel Economy Test).
- Energy distribution between the engine and battery for hybrid vehicle optimization.
- Fuel consumption trends under dynamic driving conditions.
- Battery degradation monitoring based on high-power discharge events.
- Target column (Energy Efficiency Class) categorizes vehicles into High, Medium, or Low Efficiency based on fuel use and battery degradation.

**Provider:** Ziya

**Reference:** https://www.kaggle.com/datasets/ziya07/nev-energy-management-dataset/data

