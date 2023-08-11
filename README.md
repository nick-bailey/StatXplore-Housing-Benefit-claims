# StatXplore-Housing-Benefit-claims
Repository contains code to pull data on Housing Benefit (HB) claims from the DWP's Stat-Xplore website. 

## HBen data for LSOAs - v6.Rmd
Pulls data on Housing Benefit claims for Lower Super Outputs Areas (LSOAs) in GB for 2011-21. Converts data for earlier years for 2001 LSOAs to 2011 LSOAs. Includes UC claims with housing element. 

For the setup: 
* The data on HB and UC claims are pulled from the DWP Stat-Xplore API. Users need to have a key stored in the appropriate location - see Rmd.
* Some boundary data need to be downloaded from website and read from disk - details in the code.  

The file was created as part of research into the changing geography of poverty in Britain, and in particular on the impact of welfare reforms on the suburbanisation of poverty in British cities in the decade up to the COVID-19 pandemic. For further details, see: [repository]


