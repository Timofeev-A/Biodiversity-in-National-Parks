## Introduction:

This is a data analysis report focusing on the conservation status of endangered species in USA’s National Parks with the aim to investigate patters, which could indicate why certain species become endangered.

The data was sourced through 'CodeAcademy' and demonstrate species in National Parks of the US, number of observations and their conservation status. 

There is little information about the data, as it was intent as a training set to demonstrate various data analyst skills using Python, Pandas, Numpy, Scipy and other libraries. There is no date of data collection, and it is known that the data was collected in the 7 day timeframe.

Due to human activity a lot of the species on the planet were classed according to the danger of extinction. One of those class systems was introduced by the International Union for Conservation of Nature, and probably most famously, their 'Red List' of animals. <https://www.iucnredlist.org/>

There is 423 National Parks in the US with 84 Million Acres of land in total, covering wast amounts of habitat. <https://www.nps.gov/index.htm> The parks are run by 'National Park Service'. The Park Service looks after natural and cultural resource conservation and outdoor recreation in the US.

## Scope

### Screening

Changing climate, pollution and growing cities puts the species 
at risk.
There is different levels for 'Conservation Status'. This project only looks at 5: 'Not At Risk', 'Species of Concern', 'Endangered', 'Threatened', 'In Recovery'.
The problem of endangered species is real and has a vast social impact on how we live and interact with nature.
The Data I have can play a role in solving that problem.

### Goals

The goal of this project is to understand the biodiversity in the National Parks. Which species and what category groups are most in risk. To explore the characteristics about the species and their conservations status as well as their relationship between each other. Which species are most common and least common. Does it effect their conservation status? And many more.

### Actions

The actions would be to educate and make aware people, of local biodiversity in National Parks of US. Help to protect those species and the natural habitats they are living in.

### Data

The data is provided by 'Code Academy' via the National Park Service US Department of Interrior.

It comes as two CSV databases: "species_info.csv", "observations.csv"

Traditionally the project has to be 'problem-centric', but due to the nature of this project it can only be 'data-centric', as it is the data I am required to work with, and I am limited to it.

There are 1338 rows and 7 columns in the CSV file provided, and there is no indication on how the data was collected and when it was collected. 

The "species_info.csv" file has 4 columns and 5824 rows of data. The "observations.csv" file has 3 columns and 23296 rows of data.

#### Contents
    
There is no content and column describtion, but the 'National Parks Services' was used to source the majority of the column describtions.

__category:__ Animal Category

__scientific_name:__ Binomial Name (Latin name)

__common_names:__ Adopted name for common use in the normal language

__conservation_status:__ Animal Conservation Status

__park_name:__ Name of the US National Park

__observations:__ Species Sightings

### Analysis

#### Data Analysis

Explaratory Data Analysis would be used to investigate the data.

#### Data Visualisation

For the data visualisations, I would be relying partialy at Matplotlib and Seaborn libraries.


## Conclusion

In order to reflect on the project we need to return to the goals we had in the scope:

    >The goal of this project is to understand the biodiversity in the National Parks. Which species and what category groups are most in risk. To explore the characteristics about the species and their conservations status as well as their relationship between each other. Which species are most common and least common. Does it effect their conservation status? And many more.


At the beginning of the project I have mainly worked with raw data. The data was checked for any irregularities and was cleaned up to be usable in the visualisations and analysis. The data turned out to be mostly clean and only needed insignificant alterations.

Exploratory Data Analysis was to follow, and early on it was determined that 96.72% of species in the data presented are listed as not protected. 5633 entries vs 191.

Number of visualisations were drown up to represent the findings in the EDA. 

Figure 1.1 shows that the majority of species recorded are Vascular plants (4470 of 5824), followed by Birds (521), Nonvascular Plants (333), Mammals (214), Amphibian (80) and Reptiles (79).

Out of all the species in the data frame, protected take up only 3,28% looking at Figure 1.2. Where the majority of protected species fall into 'Species of Concern' category. (2,76%) and the rest of the categories of protected species taking less then 0,50%.

Figures 2.1 to 2.5 are looking at particular species categories and their individual conservation statuses. 

We already know that Vascular plants take the biggest proportion of the data frame, and it is not that unusual to see the majority of Vascular plants taking up the biggest proportion of 'Of No Concern' class in Figure 2.1.

Things get a bit more interesting when we start looking at other classes. For example in Figure 2.2, Birds take up the most 'Species of Concern' class at just over 70 species out of the total 521, as we saw in Figure 1.1 earlier.

Figure 2.3 looks at 'Endangered' class. It is a much smaller class and it is being dominated by 7 endangered species in Mammal category. 

Following the data visualisations a table was drawn up (Chapter 4.1) to look at specific animal categories, to understand if some categories are endangered more then the others. The conservation classes were split into a simpler terms. 'Protected' species are the ones which follow into one of the classes other than 'Of No Concern'. Not protected species were the ones under 'Of No Concern' class.

Looking at a table and at percentage split of protected to not protected species in the categories we see that mammals are leading with 21,59% of species being in protection, following by the Birds at 17,87% and Amphibians at 9,59%. 

A Chi2 test was concluded to understand the difference between these three results.

Mammals and Birds were found to not have the significant difference in conservation percentage.

While the Mammals and Reptiles showed statistically significant difference. 

Unfortunately the data presented is only a practice data with no source and very limited information. 
