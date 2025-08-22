Code Files for Master's Dissertation (s2668314)

The code files consist of three main components: data, main, and result_log.

There are two main code files:

Withoutz_model: This is the original multi-stage EVRPTW under battery degradation, where the vehicle number is fixed for planning and routing.

Rolling_model: This model implements the multi-stage EVRPTW under battery degradation using a rolling decomposition approach.

Raw data consists of the classic unprocessed EVRP benchmark datasets.

Results include all experiment outputs referenced in the dissertation.
The naming conventions are as follows:

101_5C_5s_v3: Uses data file 101 with 5 customers to plan 5-stage routing using 3 vehicles.

1Ekm103_5C_3s_v3: Uses data file 101 with 5 customers to plan 5-stage routing by 3 vehicles, with energy consumption set to 1.

sXX_103_5C_5s_v3: Represents experiments with different SoH initialisations. Here, XX is alphaS, the initial state-of-health.
