## datacov: An open database of bat coronavirus surveillance (1996 to 2018)

In this repository you can find a cleaned, public-facing, simplified version of the data used by (Cohen _et al._)[https://github.com/viralemergence/batgap], "Sampling strategies and pre-pandemic surveillance gaps for bat coronaviruses"; the version of the dataset available here is intended for others to be able to use for their own research purposes. Please cite both the publication (preprint in review) and this repository (DOI forthcoming).

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
|  DetectionType   |   |
|  StudyType   |    |
|  DetectionMethod   |    |
|  DetectionMethodSpecific   |    |
|  PCRMethod   |    |
|  GeneTarget   |    |
|  GeneTargetDetailed   |    |
|  Tissue   |    |
|  Sample   |    |
|  Country   |    |
|  State   |    |
|  SamplingSite   |    |
|  Latitude   |  Sampling site latitude, if provided  |
|  Longitude   |  Sampling site longitude, if provided  |
|  nSamplingTrips   |    |
|  YearDiscrete   |    |
|  MonthsDiscrete   |    |
|  StartYear   |    |
|  StartMonth   |    |
|  EndYear   |    |
|  EndMonth   |    |
|  Summer   |    |
|  Fall   |    |
|  Winter   |    |
|  Spring   |    |
|  TerminalSampling   |    |
