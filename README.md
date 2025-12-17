# Payment Routing Optimization Analysis (Python)

This project simulates how routing decisions between three payment processors impact authorization success rate, cost per successful transaction, and revenue outcomes. This work reflects real challenges payment teams face when balancing reliability, cost efficiency, and user experience.

This work is part of my 30 Day Applied Business Strategy Challenge.

## Processor Results

### Processor A
- Success rate: 0.968  
- Failed transactions: 16  
- Total processing cost: 150  
- Cost per successful transaction: approximately 155  
- Revenue saved: approximately 82000  

### Processor B
- Success rate: 0.882  
- Failed transactions: 59  
- Total processing cost: 75  
- Cost per successful transaction: approximately 85  
- Revenue saved: approximately 72000  

### Processor C
- Success rate: 0.758  
- Failed transactions: 121  
- Total processing cost: 25  
- Cost per successful transaction: approximately 33  
- Revenue saved: approximately 61000  

## Insights

- Processor A delivers the best reliability but at a premium cost.  
- Processor B provides a strong balance between cost and performance.  
- Processor C is inexpensive but produces avoidable failures that directly reduce revenue.  
- Success rate influences revenue more strongly than processor fees.  
- The ideal routing strategy is often a combination of processors, not a single choice.  

## Visuals Included

- Success rate by processor  
- Total processing cost  
- Cost per successful transaction  
- Failed transactions  
- Routing optimization scatterplot  
- Revenue saved by processor  

## Why This Matters

Routing optimization is one of the most impactful levers for improving payment performance. Even small increases in success rate can preserve substantial revenue at scale. PMs and payment teams use simulations like this to evaluate processor performance, design routing rules, and reduce user friction.

## Tools Used

Python, pandas, numpy, matplotlib
