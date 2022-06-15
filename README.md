## datacov: An open database of bat coronavirus surveillance (1996 to 2018)

[![DOI](https://zenodo.org/badge/503452822.svg)](https://zenodo.org/badge/latestdoi/503452822)

In this repository you can find a cleaned, public-facing, simplified version of the data used by [Cohen _et al._](https://github.com/viralemergence/batgap), "Sampling strategies and pre-pandemic surveillance gaps for bat coronaviruses"; the version of the dataset available here is intended for others to be able to use for their own research purposes. 

### Suggested citation:

Please cite both of the following:

Lily E. Cohen, Anna C. Fagre, Binqi Chen, Colin J. Carlson, and Daniel J. Becker. (2022) **Sampling strategies and pre-pandemic surveillance gaps for bat coronaviruses**. Preprint DOI forthcoming.

Lily E. Cohen, Anna C. Fagre, Binqi Chen, Colin J. Carlson, and Daniel J. Becker. (2022) **datacov: An open database of bat coronavirus surveillance (1996 to 2018).** version 0.1. Downloaded from www.github.com/viralemergence/datacov on (...your date here...). DOI: 10.5281/zenodo.6644163.
 
### What's in the dataset

Each row of the dataset corresponds to the finest scale of disaggregated testing data we were able to identify based on reported sampling procedures. Each row has four fields that describe the accompanying publication:  

|  column name | description |
|  --------    |  --------------- |
|   Title |  Title of publication |
|   Authors   |   Authors of publication |
|   Journal   |   Journal of publication |
|   Year   | Year of publication  | 

All other fields describe the actual bat coronavirus prevalence data, often with several rows from each study:

|  column name | description |
|  --------    |  --------------- |
|  nSamples   |  The number of samples tested   |
|  nPositive   |  The number of samples positive for coronaviruses (as identified below)  |
|  Prevalence   |  Reported or estimated values of coronavirus prevalence across samples (should usually equal nPositive / nSamples)  |
|  HostFamily   |  The family of the bats sampled |
|  HostGenus   |  The genus of the bats sampled if provided |
|  Hosts   |  The bat host species (singular or plural, delimited by commas if pooled within the same genus) sampled if provided |
|  nSpecies   |  The number of bat species tested (if samples were pooled)  |
|  VirusGenus   |   _Alphacoronavirus_ or _Betacoronavirus_  |
|  VirusSubgenus   |   Subgenus if available, e.g., _Colacovirus_, _Sarbecovirus_  |
|  VirusStrain   |  Fine-scale viral identity, if available, e.g., "HKU8 related" |
|  DetectionType   | Detection type is split into three categories: 1) single (one estimate from a single, non-repeated sampling trip); 2) repeat (a single estimate where each repeated record represents one of multiple, longitudinal sampling trips to the same site); or 3) pooled (one estimate from the pooled results of multiple trips or sites) |
|  StudyType   |  Cross-sectional or longitudinal study   |
|  DetectionMethod   |  Type of test used (e.g.,  PCR, ELISA)  |
|  DetectionMethodSpecific   | Type of test used (more granular, if provided: e.g., hemi-nested PCR, RT-PCR, ELISA)    |
|  PCRMethod   |  Type of PCR test used if applicable (single or multiple)  |
|  GeneTarget   |  Coronavirus gene target of test, simplified (RdRp, Other, or both) |
|  GeneTargetDetailed   |  More specific information on the coronavirus gene targeted (e.g., RdRp, ORF1b)  |
|  Tissue   |  Tissues sampled (e.g.,  "faecal, rectal, or anal") |
|  Sample   |   Type of sample (e.g., "swab", "faeces") |
|  Country   |   Country of sampling site  |
|  State   |  State or province of sampling site, if reported  |
|  SamplingSite   |  Precise geospatial locality string data if reported  |
|  Latitude   |  Sampling site latitude, if provided  |
|  Longitude   |  Sampling site longitude, if provided  |
|  nSamplingTrips   |  The number of sampling trips reported as being pooled together into one set of samples  |
|  YearDiscrete   |  If sampling was a "one-time" procedure, the reported year(s) of collection  |
|  MonthsDiscrete   |  If sampling was a "one-time" procedure, the reported month(s) of collection    |
|  StartYear   |  Beginning of collection interval (year) if collection occured over a longer period  |
|  StartMonth   |  Beginning of collection interval (month) if collection occured over a longer period  |
|  EndYear   |  End of collection interval (year) if collection occured over a longer period  |
|  EndMonth   | End of collection interval (month) if collection occured over a longer period  |
|  Summer   |  Was sampling reportedly in the summer season (some samples may be pooled across seasons) - binary |
|  Fall   |  Was sampling reportedly in the autumn season (some samples may be pooled across seasons) - binary  |
|  Winter   |  Was sampling reportedly in the winter season (some samples may be pooled across seasons) - binary  |
|  Spring   |  Was sampling reportedly in the spring season (some samples may be pooled across seasons) - binary  |
|  TerminalSampling   |  Were any animals reported as being euthanized   |
