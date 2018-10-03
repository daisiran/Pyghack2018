# Pyghack 2018
Our project tackles the Urbana Fleet Fuel Management problem, which tries to find trends in gas station prices and vehicle fueling behaviors. In addition to answering these questions, we built a dynamic route recommendation system. The system calculates the route between a start point and a destination, looks at all of the gas stations that are reachable along the route, and then recommends a gas station to go to. This recommendation can be optimized for cost (i.e., it will recommend the gas station with the cheapest prices while taking into account the fuel lost by making a detour to the station) or for time (i.e., it will recommend the gas station that is fastest and cheapest to get to). 

The dynamic route recommendation system can be found at: https://lynnnyn.pythonanywhere.com

We visualized some of the insights we gained from the dataset on Tableau: 
https://public.tableau.com/views/FinalProduct/Story1?:embed=y&:display_count=yes&publish=yes

Powerpoint slides discussing our results can be found in Deliverable.pdf

We won the Grand Prize in Pyghack 2018! https://devpost.com/software/route-recommendation-using-real-time-fuel-prices
# Setting up the environment 
Run 
conda env create -f environment.yml

