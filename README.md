<h3>Description</h3>
Source code for the second coursework for the research methods course (COMP4037). This code prepares and constructs a treemap of data from a study on environmental impact of people with different diets. 

<h3>Data Source and Original Paper</h3>
The data used is not included in this repository but can be found here: https://ora.ox.ac.uk/objects/uuid:ca441840-db5a-48c8-9b82-1ec1d77c2e9c <sub>(file "Results_21Mar2022.csv")</sub><br><br>

The original study's paper can be found here: https://www.nature.com/articles/s43016-023-00795-w <sub>(Scarborough, P., Clark, M., Cobiac, L., Papier, K., Knuppel, A., Lynch, J., ... & Springmann, M. (2023). Vegans, vegetarians, fish-eaters and meat-eaters in the UK show discrepant environmental impacts. Nature Food, 4(7), 565-574.)</sub>

<h3>Repository contents:</h3>

- CW2_Build_Treemap.Rmd - R markdown file to prepare the data and construct the treemap

- CW2_Build_Treemap.html - HTML render of the R document

- Column descriptions.txt - Descriptions of each column listed in the dataset's CSV file, please read the original paper for a full description of the columns

- treemap.png - Resulting treemap saved as a png file

- treemap_rearranged.png - The same treemap as treemap.png but with diet groups reorganised. Sorting is not possible with treemapify
