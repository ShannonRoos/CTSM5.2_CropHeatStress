This is ctsm version 5.2.019 with new code including crop heat stress functions that is used in de Roos et al. (in prep, doi:) [26-07-2026]

It contains new code related to:

- outputting vegetation daytime and nighttime temperature from the LUNA model as an option (not default but can be added in user_nl_clm file)
- a new CropHeatStress module, with functions related to heat stress intensity
- impact of the heatstress (HS_factor) can be either on LAI senescence or on the reproductive stage. This now requires manual change of the HS_factor default (REP: 0 LAI: 1) and outcommenting of some lines where the impact is taking place. This is not clean but requires some final tweaks so that this can be selected in the user_clm_nl file.
- following several changes over the years, this code includes the tracking of the peak vegetation temperature during either the growing season or the grainfill stage (depending on whether the 'if cphase==grainfill' is employed)

-- EOF
