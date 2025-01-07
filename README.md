Large-Scale Route Optimization - A Real-World Scenario
A manufacturing company has warehouses in different locations and when they receive orders from their clients, a planner need to plan the item-to-truck assignment for order delivery. A delivery assignment has its associated cost determined by the type of the assigned delivery truck and the corresponding travelling distance. the optimization objective here is to minimize the overall delivery cost.

The algorithm categorizes all the items to be transported from same source (eg. City_61) to same destination (eg. City_54) as a single trip with a unique trip_id (eg. trip_1). Genetic algorithm is used to assign suitable trucks to each trip to meets trips requirement in order to minimize total transportation cost as much as possible.
Inputs: orders, distance and trucks
Orders: contains set of items to be delivered with unique item IDs, area (m2) and weight (kg)
Distance: pair of distances between sources and destinations in m.
Trucks: contains different truck types (eg. ‘1’, ‘2’, ‘3’) with their respective area (40.25, 30.25, 20.93) and weight capacity (10000, 5000, 2000)and cost per m (0.003, 0.002, 0.001).

