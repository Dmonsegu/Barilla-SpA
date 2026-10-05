# Barilla Supply Chain & Inventory Analytics

## Overview

This project applies supply chain analytics and inventory management concepts to the **Barilla supply chain case**, focusing on the challenges of demand variability, inventory control, and distributor ordering behavior.

Using Python, I recreated several analytical approaches from the case with **simulated demand and inventory data** to demonstrate how quantitative analysis can support inventory and replenishment decisions.

## Objectives

* Analyze weekly demand variability
* Evaluate inventory distributions and demand patterns
* Classify products using **ABC analysis**
* Calculate inventory **reorder points**
* Apply service-level and lead-time assumptions
* Demonstrate **Economic Order Quantity (EOQ)**
* Visualize inventory levels and replenishment thresholds
* Analyze cycle-counting accuracy
* Illustrate the **bullwhip effect** across the supply chain

## Analysis

### Demand Variability

Weekly demand was simulated using a normal distribution to demonstrate fluctuations in orders over time. Mean demand and standard deviation were used to quantify demand variability and visualize potential uncertainty in replenishment requirements.

### ABC Inventory Analysis

Products were classified into A, B, and C categories based on their relative contribution to total demand.

The analysis demonstrated how inventory resources can be prioritized:

* **A:** Highest-demand items requiring greater inventory attention
* **B:** Moderate-demand items
* **C:** Lower-demand items requiring less frequent management

### Reorder Point Analysis

Reorder points were calculated using average demand, lead time, demand variability, and a 95% service-level assumption.

The model demonstrates how safety stock can be incorporated into replenishment decisions to reduce the risk of stockouts during periods of demand uncertainty.

### Economic Order Quantity

The project also demonstrates the EOQ framework for balancing ordering and holding costs.

EOQ can help determine an economically efficient order quantity by considering:

* Demand
* Ordering cost
* Inventory holding cost

### Inventory & Cycle Counting

Additional visualizations demonstrate inventory depletion, reorder thresholds, and cycle-counting accuracy. These analyses
