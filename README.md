# Geopolitical Analysis

This project analyzes geopolitical scenarios of major countries around the world, focusing on:

- Defense budgets of countries.
- Political structures of each country.
- Strategic relations (alliances or conflicts) between countries.

A visualization graph is created to showcase how defense budgets, political structures, and relationships between countries might contribute to potential conflicts or cooperation.

---

## Data Description

The analysis uses three input files:

1. **Annual Defence Spending of countries.txt**
   - Contains the names of countries and their respective defense budgets.
   - Example:
     ```
     US, 801bn $
     China, 293bn $
     India, 76bn $
     ```

2. **Political Atomosphere within countries.txt**
   - Describes the political structure of each country.
   - Example:
     ```
     US -> Strong democracy
     China -> Strong communism
     ```

3. **Strategic Relations between countries.txt**
   - Details alliances or adversarial relationships between countries.
   - Example:
     ```
     [US, UK, Strong Allies]
     [India, Pakistan, Strong Adversary]
     ```

---

## Project Structure

- **geopolitical_analysis.py**: The main Python script to load data, process it, and create a visualization graph.
- **README.md**: Project documentation.
- **Input Files**:
  - `Annual Defence Spending of countries.txt`
  - `Political Atomosphere within countries.txt`
  - `Strategic Relations between countries.txt`

---

## How to Use

### Prerequisites
- Python 3.8+
- Required libraries: `pandas`, `networkx`, `matplotlib`

### Steps to Run:
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
