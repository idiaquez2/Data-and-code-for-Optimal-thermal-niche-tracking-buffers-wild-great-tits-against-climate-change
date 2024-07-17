Description of the data and file structure

There are four data folders, one per each of the four sets of models ran in the manuscript with all information required to replicate the analyses in the manuscript: Optimal thermal niche-tracking buffers wild great tits against climate change, by David López-Idiáquez, Ella F Cole, Charlotte E Regan & Ben C Sheldon

Folder 1: Temporal trends in the fixed intervals
This folder contained the code and data required to run the temporal trends in the fixed interval. It contains two files:

- clim_data.csv: data set containing the information on daily temperature between 1965 and 2023. It has 6 columns: date, day, month, year, min, and max. Min and max, represent the minimum and maximum temperature in º C recorded that day.

- Temporal trends in the fixed intervals.Rmd: RMarkdown file with the code required to replicate the analyses in this section.

Folder 2: Temporal trends in the relative intervals
This folder contained the code and data required to run the temporal trends in the relative intervals. It contains four files:

- clim_data.csv: data set containing the information on daily temperature between 1965 and 2023. It has 6 columns: date, day, month, year, min, and max. Min and max, represent the minimum and maximum temperature in º C recorded that day.

- gtdata ld/ gtdata hd: These two datasets contain information about the breeding data of Wytham woods great tits. They have six columns: box (nest-box name of the brood), year, April lay date (date the first egg of the brood was laid as number of days since the 1st of April), Clutch size (number of eggs laid), Mother (identity of the female that laid the clutch). Besides, gtdata hd also contains: April hatch date (hatching date of the brood as number of days since the 1st of April). These two datasets are basically the same, but gtdata hd represents the subset of gtdata ld for which hatching information was available.

- Temporal trends in the relative intervals.Rmd: RMarkdown file with the code required to replicate the analyses in this section.

Folder 3: Fitness consequences of temperature in the relative intervals
This folder contained the code and data required to run the analyses linking temperature in the relative periods and fitness. It contains two files:

- join_data4.csv: dataset containing the information on fitness and average temperature values in the 5 relative periods. It contains 13 columns: box (nest-box name of the brood), year, Clutch size (number of eggs laid), ld (laying date as days since the 1st of January), average temperature laying (average temperature at egg-laying in ºC), average temperature per1 (average temperature at incubation in ºC), average temperature per2 (average temperature in the hatching period in ºC), average temperature per3 (average temperature in the nestling period in ºC), average temperature per4 (average temperature at the fledging period in ºC). For more information on the periods see the methods of the paper.   

- breeding consequences of the relative temperatures.Rmd:  RMarkdown file with the code required to replicate the analyses in this section.

Folder 4: Thermal tracking caterpillars & mismatch
This folder contained the code and data required to run the analyses regarding the temporal trends in half-fall data and the links between temperature in the relative periods and match with the half-fall dates. It contains X files:

- Half_fall_data.csv: dataset containing half-fall information. It contains 2 columns: year and Half_fall_date (as days since the first of April, for further info on half-fall).

- clim_data.csv: data set containing information on daily temperature between 1965 and 2023. It has 6 columns: date, day, month, year, min, and max. Min and max, represent the minimum and maximum temperature in º C recorded that day.

- match.csv: data set containing information on mismatch data and temperature values in the relative periods. It contains 12 columns: box (nest-box name of the brood), year, Mother (identity of the female that laid the clutch), average temperature laying (average temperature at egg-laying in ºC), average temperature per1 (average temperature at incubation in ºC), average temperature per2 (average temperature in the hatching period in ºC), average temperature per3 (average temperature in the nestling period in ºC), Hf2 r (half-fall dates as days since the first of January), peak food (peak of food demand by the nestlings in days since the first of January) and mismatch (Hf2 r - peak food)

- thermal tracking and mismatch caterpillars.Rmd: RMarkdown file with the code required to replicate the analyses in this section.
