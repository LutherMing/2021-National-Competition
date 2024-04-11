## 🏆 National Competition
- The National Competition, also known as the National University Student Mathematical Modeling Competition, is an annual event held in China. It is the largest and most prestigious mathematical modeling competition for university students in the country. 

- The competition is open to all undergraduate students in China. Teams of three students work together to solve a set of mathematical modeling problems over a period of four days. The problems are typically based on real-world scenarios and require students to apply their mathematical knowledge and skills to develop solutions

## Restatement of the Problem

### 1. Problem Background:
- A production company specializing in construction and decorative panel materials utilizes three main types of raw materials: A, B, and C.
- The company operates on a 48-week production schedule and needs to plan raw material procurement and transportation 24 weeks in advance.
- This involves selecting raw material suppliers ("Suppliers"), determining the weekly order quantities ("Order Quantity"), selecting a third-party logistics company ("Carrier") to transport the weekly material supply from suppliers to the company's warehouse.

### 2. Known Information:
- **Production:** The company's weekly production capacity is 2.82 million cubic meters. Each cubic meter of product requires 0.6 cubic meters of type A material, 0.66 cubic meters of type B material, or 0.72 cubic meters of type C material.
- **Supply:** Suppliers may deliver more or less than the ordered quantity due to the nature of the materials. The company maintains a minimum inventory level to meet two weeks of production needs.
- **Transportation:** Materials experience a certain loss during transportation (loss rate as a percentage of the supplied quantity). Each Carrier has a weekly transportation capacity of 6000 cubic meters.
- **Cost:** Type A and B materials have purchase prices 20% and 10% higher than type C material. Transportation and storage costs are uniform for all material types.

### 3. Problem Statement:
Based on the provided information and datasets, establish a mathematical model to address the following four main issues:
1. Quantitatively analyze the supply characteristics of 402 suppliers and identify the top 50 most crucial suppliers for ensuring production continuity.
2. Determine the minimum number of suppliers needed to meet production requirements, develop cost-effective material ordering plans for the next 24 weeks, and devise transportation plans with minimal losses.
3. Develop new ordering and transportation plans to maximize purchases of type A and minimize purchases of type C materials while minimizing Carrier transportation losses. Analyze the implementation effects of these plans.
4. Determine the maximum potential increase in the company's weekly production capacity and provide material ordering and transportation plans for the next 24 weeks.


## Solution
### Summary:
The paper discusses the optimization of supply chain management for companies dealing with procurement and transportation of raw materials, which emphasizes strategic planning, data analysis, and evaluation methods to enhance efficiency and reduce costs.



1. **Problem Statement:**
   - Planning for raw material procurement and transportation in production companies.

2. **Approach:**
   - Utilized data mining to understand the current state of supply chain management and establish a supplier evaluation system.
   - Employed single-objective, multi-objective, multi-stage optimization, and modern optimization algorithms to plan the optimal solutions meeting production, storage, and transportation conditions.

3. **Model Development:**
   - Explored historical data and literature to build indicators based on supply capacity, speed, and stability.
   - Used TOPSIS evaluation method to assess 402 suppliers and identify the top 50 crucial suppliers.

4. **Predictive Analysis:**
   - Forecasted the loss rate of carriers for the next 24 weeks using adaptive filtering and time series models.

5. **Optimization Process:**
   - Implemented a multi-objective sequencing algorithm to determine the minimum number of suppliers (36) based on production and inventory needs.
   - Developed the most economical ordering strategy for the selected suppliers and optimized the minimum loss transportation plan weekly.

6. **Results:**
   - Achieved efficient ordering while maintaining reasonable low inventory costs and reduced overall transportation loss rates compared to historical averages.
   - Applied multi-objective planning to minimize production costs under relaxed constraints and flexible variables.

7. **Evaluation and Improvement:**
   - Evaluated the model's feasibility through historical data validation.
   - Improved efficiency and constraint compliance of the transportation problem using genetic algorithms.


### Code Details:
1. Python, Matlab, and Lingo codes were used.
2. TOPSIS method for comprehensive evaluation.
3. Adaptive filtering algorithm for data processing.
4. Genetic algorithm for improving transport problem solutions.

#### Evaluation:
The model was evaluated using historical data to validate the proposed solution's feasibility. Efficiency and constraint compliance of the transport problem were improved using a genetic algorithm.

#### Keywords:
Supply Chain Management, TOPSIS, Multi-objective Optimization, Time Series, Genetic Algorithm
