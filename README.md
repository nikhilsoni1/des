This repository contains sample code from a live production project. It gives a brief overview of the scalablity of the simulation models, useful in a manufacturing environment with a plethora of product families and mixes. Open source packages are extensively used.

File descriptions:

    1. er1: Simulation model of a mixed product machining system with 5 operations. (Database stream removed)
        1.1 Number of Machines: 9
        1.2 Number of fixtures (heteregenous): 26
        1.3 Number of Stations: 5
        1.4 Products: 7
    2. Hawk_Cell: Simulation model of a single product cellular machining. (Database stream removed)
    3. lead_time0.1: Calculates the lead time for all or specific products for any given period of time. Fetches data in real-time from            factory floor sensors (Databse credentials removed)
    
The 'er1' and 'Hawk_Cell' programs are extensively used for the following:

    1. Capacity planning
    2. Scenario Analysis
    3. Identifying bottlnecks
    4. Identifying crossover points (in terms of resource utilization or production volumes) from mixed product manufacturing to cellular         manufacturing
    5. KPI dashboards
