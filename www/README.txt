Metadata for data download from the online app accompanying Ruhi et al.(2017) 'Losing the pulse of the Earth's fresh waters'
Author: Mathis Messager
Date: 08/24/2017
Contact information: messamat@uw.edu
Refer to https://shiny.sesync.org/apps/gages/ for complete methodology

Ruhi et al. 2017: URL

Be aware that HUC6 IDs are in character format.
In Excel, use 'Get external data from text' to import data with the appropriate column types (delimited, data has headers, comma)
In R, use the following command line:
basin_df <- read.csv('basin_data.csv',colClasses = c('character','character','numeric','character','numeric','character','numeric','character',rep('numeric',5)))



These data are licensed under a 
Creative Common License Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)
See https://creativecommons.org/licenses/by-nc/4.0/ for details
