# Clustering Bengaluru's neighbourhoods.
### Data acquisition and cleaning 
Pincodes and their corresponding post office were obtained from [data.gov.in](https://data.gov.in/resources/all-india-pincode-directory-contact-details-along-latitude-and-longitude).Only the ‘officename’ and ‘regionname’ columns were chosen from this dataset. This dataset was then filtered to contain only pincodes in the region Bangalore. The post officename was taken as the neighborhood name, and trailing characters were cleaned. Each neighborhood name was geocoded using Nominatim. The resulting dataset was uploaded to [Kaggle](https://www.kaggle.com/rmenon1998/bangalore-neighborhoods).
