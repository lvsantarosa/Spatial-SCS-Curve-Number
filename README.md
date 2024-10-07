# Spatial SCS Curve Number

The first step to applying the SCS method is the Curve Number (CN) calculation. In this example, the Land Cover Classification project (https://mapbiomas.org/) and the Soil Grid (250 m) (see how to download here: https://github.com/lvsantarosa/Soil-Grid-on-Google-Earth-Engine) soil texture maps were used to generate a spatial CN using the `terra` package.

The complete SCS Method is available in the documents of USDA (https://nationalstormwater.com/urban-hydrology-for-small-watersheds-tr-55/)

### The following paper was written using this method:

Santarosa, L.V., Gastmans, D., Sitolini, T.P. et al. Assessment of groundwater recharge along the Guarani aquifer system outcrop zone in São Paulo State (Brazil): an important tool towards integrated management. Environ Earth Sci 80, 95 (2021). https://doi.org/10.1007/s12665-021-09382-3

Santarosa, L. V., Pinto, G. V. F., Blandón Luengas, J. S., & Gastmans, D. (2024). Remote sensing to quantify potential aquifer recharge as a complementary tool for groundwater monitoring. Hydrological Sciences Journal. https://doi.org/10.1080/02626667.2024.2412741
