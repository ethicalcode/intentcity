# `*In*Tent*City*`
Govhack 2019 Project "In Tent City"

We are a diverse team led by people experiencing homelessness. We’re using data to paint a portrait of homelessness in Victoria and to increase visibility on the services, where they are, what they are, the gaps in public data, and the surprising faces of homelessness.

# Website

# Interactive visualisations
* [Service demand vs housing affordability](https://ethicalcode.github.io/intentcity/visualisations/service_demand_vs_affordability.html)
* [Count of homeless population per region](https://ethicalcode.github.io/intentcity/visualisations/total_homeless_aurin_sa2.html)
* [Service demand vs service supply](https://ethicalcode.github.io/intentcity/visualisations/ratio_of_requests_to_providers.html)

# Data sources
Data on homelessness was drawn from the AURIN, Australian Bureau of Statistics' 2016 Census, and the Australian Institute of Health and Welfare's Specialist Homelessness Services data cubes.

To estimate the difference between Google Images and reality, we downloaded a dataset of images from the search term "homeless melbourne".  We ran the images through a [pretrained neural net](https://github.com/yu4u/age-gender-estimation) to estimate age and gender. The we compared the average age and gender of people experiencing homelessness in Google's images to the numbers from the Australian Bureau of Statistics.
