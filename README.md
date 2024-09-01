# [NDVI and Vegetation Recovery Analysis using Google Earth Engine (GEE) via nbviewer](https://nbviewer.org/github/deverestHood/Camp-Fire/blob/main/Camp_Fire_NDVI.ipynb)

## Project Overview

This project aims to analyze and quantify vegetation recovery following the 2018 Camp Fire in California. Using Landsat 8 satellite imagery, the project performs NDVI analysis to visualize changes in vegetation and calculates the difference in vegetation area between images over time. As part of this change detection analysis, satellite images from before, during, and after (recovery period) the fire were analyzed. The recovery image sequence includes images for +32, +65, +112, and +144 days (inclusive) after the Camp Fire was extinguished on 2018-11-25 to assess how well vegetation recovered from the wildfire. The project utilizes Google Earth Engine (GEE) and Folium to conduct spatial analysis and visualization of changes in vegetation area for the Butte County region.

## The Camp Fire: California's Deadliest Wildfire
The morning of November 8, 2018 brought strong winds during a critically dry point in California's wildfire season.

Just 7.5 miles outside of the town of Paradise, at approximately 6:25 AM, a fire began beneath a nearly 100 year old high-voltage electricity tower owned by PG&E (America's largest electricity company).

The fire began after an equipment failure in which a power line made contact with a steel tower, raining down shards of molten metal into dry, flammable brush.

PG&E's decision not to turn off the flow of electricity to power lines during high wind conditions in order to reduce wild fire risk ultimately led to the deadliest wildfire in the state's history, after which PG&E claimed that after considering shunting the flow of electricity to power lines, ultimately decided not to do so citing decreasing winds.

As the vegetation fire began burning along Camp Creek Road, authorities attempted to contain the fire by requesting air support in order to suppress the fire, but due to windy conditions, were unable to access the area via air. The fire quickly began spreading towards the town of Concow and its population of about 700. High winds enabled the rapid spread of the fire in multiple directions, and produced a column of smoke visible for miles.

Cal Fire's Incident Command Post and its fire officials rallied personnel in response to what had become a major fire incident. As Concow residents in the fire's path fled their homes, rescue operations began in an effort to save lives, but with aircraft grounded due to wind, and officials conducting rescue operations, they were unable to gather critical fire intelligence including the rate of its spread.

By the time the fire began making its way towards Paradise, it was already spreading at a rate of 80 football fields per minute, and would need to cross Feather River Canyon, something fires past had rarely done. As Paradise residents were just waking the morning of November 8, calls to 911 began rolling in. At the time, Paradise Police 911 dispatchers had not yet been informed of the fire by officials. After confirming the location with Cal Fire, who stated the fire was north of Concow, dispatchers continued to reassure residents that they were not in harm's way. But by 7:45, the Camp Fire had crossed Feather River Canyon, and had indeed become a threat to Paradise and its 40,000 residents. Evacuation orders were issued for residents on the east side of Paradise, but not for those from other parts of town. Soon, however, mandatory evacuations were issued for the entire town of Paradise.

With much hotter, drier, less humid summers, wildfire seasons have extended. Under these conditions, wildfires have grown larger and occur more frequently. Climate measurements gathered at weather stations have informed analyses that indicate that human-caused climate change has doubled wildfire since 1984 across the western US. In fact, Northern California summers have warmed by an average of 2.5 degrees in the last 50 years. Pervasive drought, exacerbated by hotter, drier summers further deprives wildlands of moisture, creating dry tinder perfect for the ignition and spread of catastrophic wildfires.

Only about an hour and a half after the fire started, Paradise residents found themselves surrounded by flames, ash, and smoke. Staff and patients of Feather River Hospital were forced to evacuate with little notice as patients were quickly moved to vehicles and transported from hospital grounds only to find themselves gridlocked on congested roads and highways stalling evacuees desperate to escape the hellish encroaching fire. Within an hour, the fire had swept through the town of Paradise. Winds carrying blazing embers laterally enabled the fire to spread rapidly as it consumed homes and infrastructure across simultaneous paths, rather than one distinct flaming front. This made it extremely challenging for the 350 firefighters in Paradise to identify a clear front line for them to fight the 1,800 degree inferno.

Town of Paradise emergency planners had divided the town into 14 zones that would be evacuated depending on where a fire would be coming from. During a 2008 trial run evacuation, zones on the east side of Paradise were evacuated for a fire coming from Concow. It became clear after this fire that more evacuations made it increasingly difficult to evacuate the town, so there did not exist a plan to evacuate the entire town at once. In a review after the 2008 fire, a Butte County grand jury warned that the town of Paradise had "serious capacity limitations" and provided recommendations, which included the widening of evacuation routes. The Butte County Board heeded these warnings and implemented some of the proposed recommendations, but lacked the funding necessary to widen all evacuation routes. Seeing as these roads would likely only seldomly be used in the event of large-scale evacuations, and given the cost of road widening projects, it was deemed financially unfeasible.

Thousands of Paradise residents remained in their homes as the Camp Fire swept through the town. Some residents had not received an official evacuation order, as the county sheriff's office was using a new alert system known as Code Red, which had the capacity to send out a mass alert to every Paradise resident, but the system wasn't used. Instead, alerts were sent using a different feature that informed residents (only those which had signed up to receive alerts) on a zone by zone basis. Unfortunately, over half of residents had not signed up for these alerts, and even some of those that had still did not receive potentially life-saving notifications due to downed cell phone towers. The town of Paradise was simply completely overwhelmed by the circumstances. However, the Camp Fire was not unprecedented in nature as several previous fires displayed similar characteristics, such as rate of spread and ineffectiveness of suppression efforts.

By 10:45 AM, the fire had consumed 20,000 acres, and was visible from space. By noon, it was evident that the town of Paradise had been leveled. 50,000 people managed to escape. One week after the fire started, 5,000+ firefighters were fighting the ongoing blaze from both ground and sky. For over two weeks, Paradise burned before the first rains of the winter extinguished the fire, no sooner than it had burned 153,000 acres (an area the size of Chicago), and 30,000 people had lost their homes. The Camp Fire claimed the lives of 85 people, most of which were older than 65 years of age.

November 8, 2018 is a date that will never be forgotten by, and is quite literally seared in the Paradise community's collective consciousness.

Six months after the fire, Butte County's DA Office launched an investigation to determine whether to bring forth criminal charges against PG&E whose power line had started the fire, and could possibly be charged under California Penal Code Section 452: reckless arson.

Given PG&E's long history of safety violations, including a criminal conviction for a 2010 gas explosion, its equipment has been linked to numerous destructive California fires. The company has been fined hundreds of times, and has faced fines amounting to close to $3 billion. In the months following the Camp Fire, *Wall Street Journal* reporters discovered that PG&E had been warned about its aging transmission towers whose components were likely to fail. In 2010, an outside contractor assessed equipment and determined that the average age of PG&E's transmission towers was 68 years old, though mean life expectancy is only 65 years. With climate change at play, the risks of allowing infrastructure to age in place have changed.

A statement issued by PG&E maintains that the company "disagrees with any suggestion that it knew of any specific maintenance conditions that caused the Camp Fire, and nonetheless deferred work that would have addressed those conditions" adding that "since 2010, PG&E has spent hundreds of millions on line preventative work". The company has filed for bankruptcy protection due to liabilities arising from wildfires, and it's estimated that the corporation could face at least $10.5 billion in damages from the Camp Fire alone.

As temperatures continue to rise, scientists believe that fires in California could dramatically increase in size by mid-century.

## Project Structure

The project consists of the following main components:

1. **Image Collection**: Fetching Landsat 8 images for before, during, and after the wildfire.
2. **NDVI Analysis**: Calculating NDVI for each image to assess vegetation loss and recovery.
3. **Vegetation Area Calculation**: Calculating the area of vegetation for each image and the differences between consecutive images.
4. **Visualization**: Displaying the images and calculated areas on an interactive map using Folium.

## Prerequisites

- Python 3.x
- Google Earth Engine account: Sign up for Google Earth Engine [here](https://code.earthengine.google.com/register).
- Google Colab notebook
- Necessary Python libraries: `ee`, `pandas`, `geopandas`, `folium`

## Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/deverestHood/Camp-Fire.git
   cd Camp-Fire

