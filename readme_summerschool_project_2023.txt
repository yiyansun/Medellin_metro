Data for communas:

“comunas.csv” gives the communa name, comuna id, comuna longitude, comuna latitude, municipality name, municipality id

“comunas_commutes.csv” gives the directed number of commutes (third column) between pairs of comuna ids (first two columns) in Medellín.

"communas_gmaps.csv" contains the driving times, transit times and walking times (in seconds) between the different comunas. Edge (i,j) is how long it takes to drive from i to j (at 9am in the morning during the week)

"comunas_firms.csv" gives the predicted number of commercial firms that are visible in Google Street Imagery (both formal and informal) in each comuna. 

"comunas_pop.csv" gives the average population in 2020 within each communa. 

"comunas_stratum.csv" contains the average stratum of the neighbourhoods in each comuna. Stratum is socio-economic indicator that is based on the quality of housing and infrastructure of a neighbourhood. The highest socio-economic scale is 6 (wealthy areas), and the lowest 1 (poor areas).  

Medellin metro: 

“medellin_metro.xlsx” gives the name, line, communa name, comuna id, macrozone (linked to optional shape file), municipality name and id, latitude, longitude, stop type (metro, bus rapid transit, cable, or tramway), and transfer indicator for each metro stop. Subsequent rows on the same line share an edge. Some stops are repeated, as they are on multiple lines (transfer points).

Optional Data: 

"communa_boundaries" gives the shape files of all the communas that can  be used if you would like to use any other open data available online.
