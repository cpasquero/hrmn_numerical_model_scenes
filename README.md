# hrmn_numerical_model_scenes
In this repository, netcdf files are available containing the following variables from some WRF numerical simulations:
- sst: sea surface temperature [K];
- u10, v10: zonal and meridional 10m wind components (u10 is positive eastward and v10 is positive northward) [m/s];
- seamask: 1 over the sea and 0 elsewhere (optional field);
- wind_div: surface wind divergence [1/s] (optional field);
- uc, vc: ocean surface currents [m/s] (available only when the simulation is coupled to the CROCO ocean model);

The files might contain 'd01', 'd02' or 'd03' in their names. This refers to the original WRF nested domain: the higher the domain number, the higher the spatial resolution.

For each domain, there is a reference paper that describes the numerical setup, the area and time period of interest.
1. Ligurian Sea: Meroni, Renault, Parodi and Pasquero (2018) https://doi.org/10.1007/s00024-018-2002-y
2. EUREC4A: Tartaglione et al. (2024) https://doi.org/10.1002/asl.1208
3. Western Mediterranean: Renault, Arsouze and Ballabrera-Poy (2021) https://doi.org/10.1029/2020JC016664
