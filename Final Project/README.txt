# Project Assignment #1: Project Proposal

This is all just brainstorming for now...

## An introduction of your research question
The proposed project seeks to examine who, by demographic and socioeconomic status, is most likely to own a car, particularly a “clean” vehicle (e.g. Hybrid, electric or alternative fuel that is not fossil fuel). The lack of a private vehicle can limit one’s ability to travel far, to access opportunities and distant services. The project will also examine other characteristics of the vehicle stock for those who own a vehicle. (e.g. the age of their vehicle, fuel type). The project is meant to provide a snapshot of the characteristics of vehicle ownership.

## An explanation of why it is important to you, why it matters to others, and what is at stake
In September of 2020, California Governor Gavin Newsom issued an executive order that would ban the sale of new gasoline-powered cars by 2035. All new cars and passenger trucks sold in the state will be zero-emission vehicles. This move is part of the state’s long-term goal of reducing fossil fuel reliance and its commitment to fight against climate change. It is therefore important to get a sense of the current landscape of vehicl ownership - who is more likely to own a vehicle, what are some key characteristics of their vehicle (e.g. age of vehicle, fuel type, mileage), and possibly barriers to vehicle ownership.

## A preliminary description of data sources that you will use
This project will pull in a travel survey dataset called the **[National Household Travel Survey (NHTS)](https://nhts.ornl.gov/)**

"Conducted by the Federal Highway Administration, the NHTS is the authoritative source on the travel behavior of the American public. It is the only source of national data that allows one to analyze trends in personal and household travel. It includes daily non-commercial travel by all modes, including characteristics of the people traveling, their household, and their vehicles."

I am also proposing to pull in some census tract level data from the **[American Community Survey (ACS)](https://www.census.gov/data/developers/data-sets/acs-5year.html)** on vehicle ownership and a socioeconomic indicator. 
## A scope that explains the intended analysis and resulting visualizations for your project

Some topics I want to cover or analyze include:
* Who is more likely to own a vehicle? And what are their characteristics? (by demographic and socioeconomic status)
* Who is more likely to own a clean vehicle (Hybrid, electric or alternative fuel)? 
* What are the characteristics of the vehicle stock for thos with a car?
    * What is the average age of their vehicles?
    * Who is more likely to own older vehicles? For example, we can define this as 20 years or older using the age of the vehicle variable.
* Who is more likely to struggle with paying for gas? The vehicle file includes a variable called 'PRICE' (Price of Gasoline Affects Travel). Although the dataset is a little outdated (2017), it can nonetheless gives us a sense of who was struggling to pay for gas in 2017 and who may be struggling to pay for gas now with the prices very high.

Based on these key questions, I can see myself creating a series of plots including bar charts, histograms, and scatter plots to visuallize the findings. The guideline for the final project also calls for a modeling component. In this case, I may model vehicle ownership and include a series of explanatory variables. Additionally, I would like to include a few maps created through Python that displays the spatial distribution by neighobrhoods (census tracts) of vehicle ownership, vehicle type, and a socieocnomic status indicator. The maps will help visually compare some key indicators to see if there is a relationship. I'm hoping to just narrow the maps to Los Angeles County (instead of all CA) as an example. I am excited to learn more about Python mapping for data visualization! (assuming I can get geopanda installed on my comptuer! so far it hasn't worked)

### A concluding paragraph of what insights you expect to gain from your research

I hope the research project can provide a "snapshot" into vehicle ownership in CA, with findings on: a breakdown by race and income on who has and who doesn't have a vehicle (automobile) to travel in CA?; for those with a vehicle, what is the characteristics of their vehicles?; what areas in Los Angeles County has a higher share of older vehicles? cleaner vehicles (from the Python mapping component of this project)

More to come...
