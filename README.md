# United Oil – Blending Optimization (Pyomo)

This project solves a gasoline blending optimization problem for United Oil using
Linear Programming and an abstract Pyomo model.

## Problem Overview
United Oil produces Regular, Mid-Grade, and Premium gasoline by blending different
crude streams. The objective is to maximize weekly profit while satisfying:

- Crude oil supply limits
- Gasoline demand requirements
- Octane rating specifications
- Vapor pressure constraints

## Methodology
- Linear Programming (LP)
- Abstract modeling with Pyomo
- Multiple gasoline grades and crude inputs
- Scenario-based data files (.dat)

## Decision Variables
- Amount of each crude used in each gasoline blend
- Total production per gasoline grade

## Objective Function
Maximize total profit:
- Revenue from gasoline sales
- Minus cost of crude inputs

## Constraints
- Supply availability
- Demand satisfaction
- Weighted-average octane limits
- Maximum vapor pressure limits

## Tech Stack
- Python
- Pyomo
- Linear Optimization

## How to Run
```bash
pip install -r requirements.txt
python blending_model.py data/scenario_1.dat
