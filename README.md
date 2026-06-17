# DynQual

The dynamical surface water quality model (DynQual) is a large scale water quality model for simulating hydrology (e.g. discharge, water withdrawals, etc) and surface water quality (e.g. water temperature, TDS, BOD, FC, etc) at multiple spatial resolutions (30 arcmin, 5 arcmin) with a daily, weekly, monthly or annual reporting timestep. 

This repository contains the most recent (development) version of DynQual, with the stable version (DynQual v1.0) avaliable here: https://github.com/UU-Hydro/DYNQUAL.

DynQual builds on the global hydrological model PCR-GLOBWB2 (Sutanudjaja et al., 2018; https://github.com/UU-Hydro/PCR-GLOBWB_model) and the water temperature model DynWat (Wanders et al., 2019; https://github.com/wande001/dynWat), allowing for both the quantification of pollutant emissions from different human water use activities and their subsequent routing through the surface water network.

This repository holds an installation guide and the model scripts for running DynQual (DynQual_Manual.md).

**Contact (DynQual)**: Edward R. Jones (e.r.jones@uu.nl)

**Contact (PCR-GLOBWB2)**: Edwin H. Sutanudjaja (E.H.Sutanudjaja@uu.nl). 

### Main references/ papers:
**DynQual**: Jones, E. R., Bierkens, M. F. P., Wanders, N., Sutanudjaja, E. H., van Beek, L. P. H., and van Vliet, M. T. H.: DynQual v1.0: a high-resolution global surface water quality model, Geosci. Model Dev., 16, 4481–4500, https://doi.org/10.5194/gmd-16-4481-2023, 2023.

**PCR-GLOBWB2**: Sutanudjaja, E. H., van Beek, R., Wanders, N., Wada, Y., Bosmans, J. H. C., Drost, N., van der Ent, R. J., de Graaf, I. E. M., Hoch, J. M., de Jong, K., Karssenberg, D., López López, P., Peßenteiner, S., Schmitz, O., Straatsma, M. W., Vannametee, E., Wisser, D., and Bierkens, M. F. P. (2018). PCR-GLOBWB 2: a 5 arcmin global hydrological and water resources model, Geosci. Model Dev., 11, 2429-2453, https://doi.org/10.5194/gmd-11-2429-2018.

**DynWat**: Wanders, N., van Vliet, M. T., Wada, Y., Bierkens, M. F., & van Beek, L. P. (2019). High‐resolution global water temperature modeling. Water Resources Research, 55(4), 2760-2778, https://doi.org/10.1029/2018WR023250
