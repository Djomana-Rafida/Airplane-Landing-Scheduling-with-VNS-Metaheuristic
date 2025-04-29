# Airplane Landing Scheduling with Metaheuristics (Project Delta)

## Objective

Minimize the total deviation from preferred landing times for a set of aircraft.

---

## Problem Structure

- **Inputs**:
  - List of aircraft with:
    - Preferred landing times
    - Time windows
    - Separation times between consecutive landings

- **Constraints**:
  - Respect aircraft time windows
  - Maintain minimum separation time between landings

---

## Metaheuristic

- **Approach**: Variable Neighborhood Search (VNS)

---

## Datasets

- Provided in `.csv` format  
- Source: EUROCONTROL

---

## Evaluation Metrics

- **Objective Function**:  
  Total deviation from preferred landing times
