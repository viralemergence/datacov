## datacov: An open database of bat coronavirus surveillance (1996 to 2018)

In this repository you can find a cleaned, public-facing, simplified version of the data used by [Cohen _et al._](https://github.com/viralemergence/batgap), "Sampling strategies and pre-pandemic surveillance gaps for bat coronaviruses"; the version of the dataset available here is intended for others to be able to use for their own research purposes. Please cite both the publication (preprint in review) and this repository (DOI forthcoming).

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
|  Prevalence   |  Reported vor estimated values (should usually equal nPositive / nSamples)  |
|  Host   |  The bat host species or higher taxonomy identified  |
|  nSpecies   |  The number of bat species tested (if samples were pooled)  |
|  VirusGenus   |   _Alphacoronavirus_ or _Betacoronavirus_  |
|  VirusSubgenus   |   Subgenus if available, e.g., _Colacovirus_, _Sarbecovirus_  |
|  VirusStrain   |  Fine-scale viral identity, if available, e.g., "HKU8 related" |
|  DetectionType   | Spatiotemporal scale of sampling: single (one site, one trip), repeat (same site over multiple trips), or pooled (multiple sites, multiple trips) |
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
