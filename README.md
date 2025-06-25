# Radiative-kernels
Netcdf files containing data for radiative kernels. 

## Ozone kernel data

3D-fields with normalized radiative forcing values for gases and aerosols.

* The file NFRO3v6_OsloRF.nc contains radiative kernel data for ozone.

* The file NFRO3v6_TOA_OsloRF.nc is the same as NFRO3v6_OsloRF.nc except that it is for top-of-atmosphere (TOA) forcing instead of tropopause.

* The file aerocom.OsloCTM2.A2.CTRL.monthly.levelheight.nc specifies the monthly pressure and level heights of the ozone kernel

The data are documented in the article [Skeie et al. 2020](https://www.nature.com/articles/s41612-020-00131-0) and and Collins et al. (in prep.)

Author: Øivind Hodnebrog

## PDRMIP kernel data

* The file pdrmip_toa_rtkv2_albedo_T42_monthly.nc include radiative effects from surface albedo changes, and pdrmip_atm_rtkv2_albedo_T42_monthly.nc is the atmospheric radiative heating kernel for the same.

* The file pdrmip_toa_rtkv2_surfdT_T42_monthly.nc include radiative effects from surface temperature changes, and pdrmip_atm_rtkv2_surfdT_T42_monthly.nc is the atmospheric radiative heating kernel for the same.

* The file pdrmip_toa_rtkv2_vertdT_T42L60_monthly.nc include radiative effects from atmospheric temperature changes, and pdrmip_atm_rtkv2_vertdT_T42L60_monthly.nc is the atmospheric radiative heating kernel for the same.

These data are documented in the article [Myhre et al. 2018](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2018GL079474)

Author: Gunnar Myhre

## Aerosol direct radiative forcing kernel

* The file VP_NRF_4D_L60_V2_MM.nc contains 4D fields (lon, lat, lev, month) of normalized direct radiative forcing per unit aerosol mass, for three species:
  - nrf_bcff: BC aerosols from fossil fuel emissions
  - nrf_oc: Organic carbon aerosols
  - nrf_so4: Sulfate aerosols

The calculations and the radiative properties assumed for the aerosols are documented in [Samset and Myhre 2011, GRL](https://doi.org/10.1029/2011GL049697)

Author: Bjørn H. Samset and Gunnar Myhre
