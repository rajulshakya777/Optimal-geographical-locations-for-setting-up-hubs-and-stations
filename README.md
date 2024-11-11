# Optimal-geographical-locations-for-setting-up-hubs-and-stations
I have develped a program to find the optimal to determine the most optimised location to build our hubs and stations for providing medicines and medical equipments using drones in remote areas of aAndman Nicobar Islands where the supply of these things are very difficult.
This subset will find perfect positions of hubs and spokes to be placed in different geographies to meet specific condition such that:
to have a distance of 100 km in between 2 hubs, 5 stations in between them with minimum distance of 20 km between two stations. Also we will take into account the requirement to have atleast 2 healthcare business in the vicinity of 25sqkm area of each station.
Factors to consider for setting up HUB:

- Nearby Hospital,
- Availability of Electricity(High),
- Population in region (Dense),


Factors to consider for setting up Station:
- Nearby Primary health centres,
- Nearby Healthcare Businesses
- Availability of Electricity(Moderate or less),
- Population in regions(Sparse),

I have used k means clustering algorithm to find such points
