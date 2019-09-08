# `*In*Tent*City*`
Govhack 2019 Project "In Tent City"

We are a diverse team led by people experiencing homelessness. We’re using data to paint a portrait of homelessness in Victoria and to increase visibility on the services, where they are, what they are, the gaps in public data, and the surprising faces of homelessness.

# Interactive visualisations
* [Service demand vs housing affordability](https://ethicalcode.github.io/intentcity/visualisations/service_demand_vs_affordability.html)
* [Count of homeless population per region](https://ethicalcode.github.io/intentcity/visualisations/total_homeless_aurin_sa2.html)
* [Service demand vs service supply](https://ethicalcode.github.io/intentcity/visualisations/ratio_of_requests_to_providers.html)

# Data sources
Data on homelessness was drawn from [AURIN](https://data.aurin.org.au/dataset/au-govt-abs-sa2-estimating-homelessness-2016-sa2-2016), the [Australian Bureau of Statistics' 2016 Census](https://www.abs.gov.au/AUSSTATS/abs@.nsf/Latestproducts/2049.0.55.002Main%20Features12016?opendocument&tabname=Summary&prodno=2049.0.55.002&issue=2016&num=&view=), and the Australian Institute of Health and Welfare's [Specialist Homelessness Services data cubes](https://www.aihw.gov.au/reports-data/health-welfare-services/homelessness-services/data) and [data tables on rough sleepers](https://www.aihw.gov.au/reports/homelessness-services/sleeping-rough-profile-shs-clients/data). Data on service demand vs. supply was drawn from [Ask Izzy](https://opendata.askizzy.org.au/).

To estimate the difference between Google Images and reality, we downloaded a dataset of images from the search term "homeless melbourne".  We ran the images through a [pretrained neural net](https://github.com/yu4u/age-gender-estimation) to estimate age and gender. The we compared the average age and gender of people experiencing homelessness in Google's images to the numbers from the Australian Bureau of Statistics.
