# Environmental Data Analysis - Datasets for Lab 2 on the Distribution and Descriptive Statistics

This is a repository containing a working dataset for the teaching of an undergraduate course at the University of Hong Kong. 

## General Information

__Project Title__: Movement ecology of Beale's eyed turtles (_Sacalia bealei_)

__Author__: Wing Sing Chan

__Dates of data collection__: 2020-2021

__Geographical location of data collection__: Hong Kong

## Project Description
Asian turtle populations have declined substantially over past decades due largely to over-collection of wild individuals for food consumption, traditional medicines and pet trade. With many being threatened to extinction, the needs to understand the spatial ecology of those at risk has been pivotal in delineating species specific management strategy and conservation plan. 

In this study, we aimed to characterize home range, movement patterns, and microhabitat use of Beale’s eyed turtles (_Sacalia bealei_), an endangered species listed by the International Union for Conservation and Nature (IUCN). Across the 2-year study period, we monitored 25 individual _S. belaei_ (12 females, 8 juvniles, and 5 males) within a natural stream in Hong Kong. Each individual was outfitted with a radio transmitter (model SOPR-2190; model SOPR-2038, Wildlife Materials International Inc., Illinois) and relocated two to four times per week using a telemetry receiver (IC-R10, ICOM Inc., Kirdland, WA) and a 3-element Yagi antenna (Biotrack Ltd. Wareham, United Kingdom). Location of individual turtle was determined by triangulation and identified with a GPS coordinate using Garman GPSMAP® 62s. Date, time, weather information, habitat type, microhabitat measurements and behaviour of individual turtles were noted.

## Dataset Description
The file `SABE_homerange2.csv` in the repository is a summarised dataset that contained __biometric data__ and __home range characterization__ of _S. bealei_ calculated from the relocation data collected during the period from May 2020 to Aug 2021. Variables in the dataset include the followings, 

- `ID` is a unique number assigned for each captured individual and identified through a marginal scale notching system developed by Cagle (1939).

- `Sex` is differentiated by visual examination of the secondary sexual characteristics into female (F) and male (M) for adults. Individuals whose measured carapace length smaller than 90 mm were otherwise considered juvenile (J). 

- `CL` is the straight-line carapace length measured using a caliper at the start of the tracking period for each monitored turtle. Measurement unit is in millimeter (mm).

- `PL` is the straight-line plastron length measured using a caliper at the start of the tracking period for each monitored turtle. Measurement unit is in millimeter (mm). 

- `Wt` is the body mass of individual turtle weighted using an electronic balance at the start of the tracking period. Measurment unit is in gram (g).

- `Season` was categorised based on the environmental condition in Hong Kong and the biological timing of _S. bealei_, and was divided into 5 mutually exclusive categories (2020 Wet Season, 2020 Mating Season, 2020 Dry Season, 2021 Nesting Season, and 2021 Wet Season). 

- `StartDate` and `EndDate` indicate the period of the defined season. 

- `HR_Type` specifies the method used for estimation of the home range type. Here, the dataset only included the home ranges estimated using minimum convex polygon (MCP). 

- `MCP_Lv` defines the percentage of the points used for the drawing of the MCP. Here, only 100% MCPs are presented in the dataset

- `Area_m2` is the calculated home range size (m^2^) for the corresponding individuals of the specified season. 

## Contact Information
This work is not the direct research output of the study project. The dataset constituted only a part of an ongoing research project and has been modified to suit the purpose of teaching. If you have any actual concern related to the research project or the dataset itself, please contact he project author Wing Sing Chan at wschan19@connect.hku.hk. 


This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution - Non-Commercial 4.0 International License</a>.<br />
<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commos License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a>
