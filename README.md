Data to go with the paper “Can we reduce phosphorus runoff from agricultural fields by stimulating soil biota?”
There were three bouts of soil sampling as outlined below:
three sampling boughts took place one field harvest on July 13th and 15th
the second took was field harvested on September 9th and 11th
The third was harvested on September 30th

Description of files:

Soil data files:
summary.Na_addition.resin.csv - concentrations of C  N  and P concentrations from the resin strips using the methods described in the paper Can we reduce phosphorus runoff from agricultural fields by stimulating soil biota?
	Key to column titles
		Date - Date sample taken coded as YYYYMMDD
		sample - Indicates the plot number
		block - Indicates which 2mx2m block the sample was taken from
		field - Indicates which of the 4 fields the sample was taken from
		treatment - "The treatment the soils received; either corn stover addition; Na addition; both stover and Na additoin; or control"
		treat.na - "Indicates whether na was added; 0=FALSE; 1=TRUE"
		treat.stover - "Indicates if stover was added; 0=FALSE; 1 = TRUE"
		TOC - Total organic C. Reported in µg C / cm^2 resin strip / day
		TN - Total extractable N. Reported in µg N / cm^2 resin strip / day
		P - Total P. Reported in µg P / cm^2 resin strip / day
		days - number of days resin strip in the ground

summary.Na_addition.soil_samples.csv - data collected from soil samples using the methods described in the paper Can we reduce phosphorus runoff from agricultural fields by stimulating soil biota?

	Key to column titles
		bout - the bought number; note that I am bad at spelling and the poor spelling was kept for consistency
		datecode - Date sample taken coded as YYYYMMDD
		sample - Indicates the plot number
		block - Indicates which 2mx2m block the sample was taken from
		field - Indicates which of the 4 fields the sample was taken from
		treatment - The treatment the soils received either corn stover addition Na addition both stover and Na additoin or control
		treat.na - Indicates whether na was added 0=FALSE 1=TRUE
		treat.stover - Indicates if stover was added 0=FALSE 1=TRUE
		pH - Soil pH measured with 10:1 nanopure water:dry soil
		gdry_gwet - soil dryweight in ratio of g dry soil : g of wet soil
		co2 - Respiration of soils measured on an IRGA in the lab at 55% water holding capacity in ug-C respired/g dry soil / day
		toc.k2so4 - Total extractable organic carbon in ug C/g dry soil extracted by K2SO4
		tn.k2so4 - Total extractable N in ug N/g dry soil extracted by K2SO4
		toc.h2o - µg C/g dry soil in fumigated samples extracted by K2SO4
		tn.h2o - µg N/g dry soil in fumigated samples extracted by K2SO4
		fum.c - µg C/g dry soil in microbes defined as fum.c - toc.k2so4
		fum.n - µg N/g dry soil in microbes defined as fum.n - tn.k2so4
		p.k2so4 - µg PO4-P/g dry soil extracted by K2SO4
		p.fum - µg PO4-P/g dry soil in fumigated samples extracted by K2SO4
		p.h2o - µg PO4-P/ g dry soil extracted by H2O
		p.bicarb - µg PO4-P/g dry soil extracted by bicarbonate solution (Olsen P)
		bg - B-glucosidiodase activity. Reprted in activity (nmol/h/g dry soil)
		lap - Leucine amino peptidase activity. Reported in activity (nmol/h/g dry soil)
		nag - n-aceytl-glucoaminadases. Reported in activity (nmol/h/g dry soil)
		phos - phosphotase. Reported in activity (nmol/h/g dry soil)
		na - measured soil sodium concentration. Only take 1st and last bout (bouts 1 and 3) µg-Na/g dry soil.
		p.total - total soil phosphorus contration µg P/g dry soil. Only take 1st and last bout (bouts 1 and 3)
		n.percent - percentage of soil (by mass) that was nitrogen as determined by the CHN analyzer vario micro cube select (Elementar; Ronkonkoma NY) in the USDA-ARS lab located at the University of Toledo in Toledo OH; Only measured for the 1st and last bouts
		c.percent - percentage of soil (by mass) that was carbon as determined by the CHN analyzer vario micro cube select (Elementar; Ronkonkoma NY) in the USDA-ARS lab located at the University of Toledo in Toledo OH; Only measured for the 1st and last bouts


	Key to non-value codes
		NS - not enough sample  to run assay
		NR - sample needs to be rerun on assay
		0.00001 - Below assay detection limit

Invertebrate data files:

community_all.csv - data on community composition of the invertebrates caught in pitfall traps 

family_all.csv - data on family composition of invertebrates caught in pitfall traps 

functional.group_all.csv - data on the functional groups of the invertebrates caught in the pitfall traps 

order_all.csv - data on order composition of invertebrates caught in pitfall traps 
	
notes on invert species - notes from the Pelini Lab on  the invertebrate species caught


Decomp bag data files:

bag.decomp.csv - Organic matter (determined by combustion) present in the decomposition bags at the end of the experiment 

decomp.bags_summary.csv - Data on invertebrates harvested from decomposition bags 


R code:

importing data_v2.Rmd - the rcode used to import and clean up data for further analysis 

mixed effects models code.Rmd - R code use for mixed-effects models 
