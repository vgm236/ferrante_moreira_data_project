# Ferrante-Moreira Data Project
This notebook was prepared by:

Alex Ferrante (af3913@nyu.edu)

Vinicius Moreira (vgm236@nyu.edu)

Graduate School of Arts and Science (GSAS) at New York University (NYU)

December 2021

This repository investigates the behavior of the labor market in the United States during the COVID-19 crisis. We download the data through the Bureau of Labor Statistics (BLS) API for the US and all its states to compare the data within them over time and across states. We also aim to detect any potential effect of different policies in generating diverging labor market trends in those states.

We see that the participation and unemployment rates have been almost monotonically decreasing since the beginning of the 2000s and that COVID-19 crisis seems to have exacerbated the downward trend on participation, at the same time that the rise and fall of the unemployment rate as unprecedentedly fast. This is also true when we do a cross-state analysis, but the dispersion was high following the COVID-19 shock. 

In terms of distinguishing whether an early or late date had an impact on the unemployment or the participation rate, we found an interesting dynamics where states that ended the program later saw an increase in participation rates whereas those that ended the program earlier saw a decrease in participation rates. 

This divergence between "late" and "early" states seemingly contradicts the permanent income hypothesis. This is particularly true when we visit states with similar characteristics. However, most of the "late" states ended the program by September, when there was a spike in the participation rate, which would be more aligned with the permanent income hypothesis.

However, it is also hard to see the direction of the causality. These findings could either mean that the Pandemic Unemployment Assistance ended earlier in some states because their labor markets were already doing better or the PUA make these markets worse off.

This is part of the QuantEcon class at NYU called Data Skills for Computational Social Science, taught by Drs. Thomas Sargent, Spencer Lyon and Chase Coleman.
