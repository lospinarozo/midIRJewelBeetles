ReadME Output files


NIRVISOpticalProperties

It is the result of multiplying the reflectivity and transmissivity measurements times the sun irradiance, then calculating a ratio of the area under the curve (AUC) of the product curve divided by the AUC of the sun irradiance. 

columns: 

SppTreat =  species and treatment. 
spot =  whether the measurement was obtained from a light spot in the elytra or a dark spot
value =  calculated proportion of light interacting with the elytra for each optical property
Oprop =  Absorptivity, transmissivity or reflectivity. It is expected that the sum of these three values for a given species  is 100%
manip =  this is the same as the treatment, indicating whether the elytra had been scraped or measured intact.
alpha =  parameter only used for the alpha displayed in the plot. 


midIRproperties

This file is the result of calculations of emissivity values in the proximity of a black body radiator at different temperatures. This was obtained by multiplying the measured midIR properties times the irradiance of a black body. Then, calculating the area under the curve (AUC) of the product curve and dividing by the AUC of the original black body radiation. 

columns:

spp =  species
bbTemp = these are the temperatures at which the black body was assumed to be in kelvin: 293, 300, 321, 333, 343 and 293.
Measurement = AUCTr means Transmittance, AUCRf means reflectance and Emiss means emissivity. It is expected that the sum of these three values for a given species  is 1.
Ely response =  the values calculated for each optical property. In other words, the proportion of long wavelengths interacting with the elytra by each of the three properties. 