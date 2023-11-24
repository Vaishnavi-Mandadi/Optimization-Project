# **Gasoline Blending Optimization Project**

## **Overview**
This project, part of the Advanced Business Analytics course at the Barton School of Business, addresses the Gasoline Blending Problem faced by Jansen Gas. The objective is to develop an optimization model to maximize revenue from blending and selling three types of aviation gasoline (avgas) - A, B, and C - by using four different feedstocks.

## **Problem Description**
Jansen Gas blends avgas using Alkylate, Catalytic Cracked Gasoline, Straight Run Gasoline, and Isopentane. Each feedstock varies in availability, cost, Reid vapor pressure, and octane rating. The blending process must adhere to specific chemical requirements for each gas type while maximizing overall revenue.

## **Approach and Methodology**
Objective: Maximize total revenue from producing and selling gasoline blends.

Mathematical Formulation: Linear programming model with decision variables representing the quantities of each feedstock used in each gasoline blend.

Tools Used: Python with PuLP library for linear programming; Pandas for data handling.

## **Implementation Steps**
Data Setup: Import libraries (PuLP and Pandas), set up feedstock and gasoline data.

LP Problem Definition: Define the linear programming problem to maximize revenue.

Decision Variables: Establish variables for the quantity of feedstock in each blend.

Objective Function: Define revenue calculation from selling gasoline and leftover feedstocks.

Constraints: Set constraints for Reid vapor pressure, octane rating, and production requirements.

## **Results**
The model successfully identifies the optimal blending plan.
Maximum revenue obtained: $1,718,021.80.

## **Sensitivity Analysis**
Detailed analysis of each constraint's impact on the objective function.
Understanding of resource utilization and capacity constraints.

## **Conclusion**
The project demonstrates the effective application of linear programming in solving a real-world blending problem, resulting in an optimal strategy for maximizing revenue.

## **Repository Contents**
Python scripts for the linear programming model.
Data files for feedstock and gasoline properties.
Jupyter Notebooks detailing the problem-solving approach and results.

## **Requirements**
Python 3.x
PuLP
Pandas
