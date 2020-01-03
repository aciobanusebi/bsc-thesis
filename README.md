# BSc Thesis

**Language**: Romanian

**Title**: Visualization and analysis of spatial data

**Demo**: demo.webm

2017 summer, FII, UAIC, Iasi, Romania

**Abstract**:

The **problem** tackled here is the following: given **point data** (Latitude, Longitude) or **zone data** (polygons) which is mapped on a world map, how can it be **visualized to reveal additional information associated with it** (e.g., the number of bedrooms of a house; the
number of students from a school district)? 

The **solution** has **two components**: 
- the coloring based on one attribute and 
- the coloring based on two or more attributes. 

Since for the coloring based on one attribute, a **unidimensional color gradient** was used and the color represented the value of the attribute (e.g., red for the greatest value and yellow for the lowest value), for the coloring based on two or more attributes a **bidimensional color gradient** was used and the color represented the similarity between instances: two similar instances in the input space will have associated two similar colors (e.g.: two red points on the map are similar; a red point and a green point on the map are dissimilar). The coloring based on two or more attributes was realized with the aid of **Self‐Organizing Maps (SOM) algorithm**. 

Some **difficulties** occurred – the lack of documentation regarding the relatively new technology (shiny) and the understanding of the link between SOM algorithm and colors –, but there is a final result: an interactive Web application created in **R** with the *shiny* package.
