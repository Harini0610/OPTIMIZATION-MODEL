# OPTIMIZATION-MODEL

COMPANY: CODTECH IT SOLUTIONS

NAME: HARINI P

INTERN ID: CT04DH454

DOMAIN: DATA SCIENCE

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH KUMAR

# DESCRIPTION

EDITOR USED: VISUAL STUDIOS

For Task 4 of my Data Science internship, I worked on a Warehouse Optimization Problem using Linear Programming (LP). This project was all about minimizing the overall operational cost of opening warehouses and transporting goods to different cities, while still satisfying demand. I really enjoyed this task as it gave me a practical understanding of optimization problems in supply chain logistics.

In this project, I used Python along with the pulp library, which is a powerful LP solver. I had 3 potential warehouse locations (W1, W2, W3) and 5 cities (C1 to C5) that need goods. Each warehouse had a fixed cost associated with opening it, and there were also shipping costs between each warehouse and each city. My objective was to decide which warehouses to open and how much quantity to ship from each one to the cities, such that the total cost (fixed + shipping) is minimized and each city's demand is fully met.

1. I first created decision variables:

 *Binary variables to indicate whether a warehouse is used.

 *Continuous variables to represent how much quantity is shipped from each warehouse to each city.

2. Then I wrote the objective function to minimize:

Total fixed cost for using warehouses + Total shipping cost.

3. I added constraints:
Each city’s demand must be fully satisfied.
Shipping should only happen from warehouses that are open.

After solving the problem using pulp, I printed the total cost, warehouses selected, and detailed shipment quantities. The LP solution gave an optimal cost of $12,560, and only Warehouse W1 was chosen. All demand was fulfilled efficiently from just this one warehouse.

To visualize the solution, I plotted a simple map using matplotlib, with mock coordinates assigned to warehouses and cities. I used arrows to show shipment routes. This really helped in understanding the geographical aspect of the solution and how optimization affects logistics in real space.

Insights:

The model smartly avoids opening all warehouses and chooses the one with the most cost-effective shipping routes.

All city demands are fully met.

The visualization gives a nice real-world picture of how goods flow from warehouses to cities.

Overall, Task 4 gave me a solid grip on solving linear programming problems in real-world scenarios like logistics and supply chain. It helped me connect mathematical modeling with business decision-making and data visualization—making this task both analytical and creative!



