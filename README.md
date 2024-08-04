# Exploring-wildlife-GIS-Data
**Overview**
This project explores the International Union for Conservation of Nature (IUCN) geospatial database for terrestrial mammals. The dataset provides habitat information for over 12,000 mammal species worldwide. The goal is to analyze the dataset to understand species distributions, visualize habitat data, and gain insights for conservation efforts.

**Project Structure**

**1. Statistical Exploration**

Dataset Parsing:

We begin by examining the dataset to determine the number of records and attributes. This initial analysis helps us understand the scope and structure of the data.

**Taxonomical Categories:**

We analyze the distribution of mammal species across various taxonomical categories such as kingdom, phylum, class, order, family, and genus. This helps in understanding the classification and diversity of species in the dataset.

**Habitat Types:**

The dataset includes information about different habitat attributes, including presence, origin, and seasonal characteristics. We explore these attributes to understand the types and distribution of habitats.

**Meta-Information:**

We review metadata such as the data compiler, citation sources, and compilation years. This provides context on the dataset's origin and the reliability of the information.
Endangerment Information:

Species are categorized by their conservation status. We analyze these categories to visualize the distribution of endangered species and understand the conservation challenges.


**2. Geospatial Exploration**

**Habitat Size Distribution:**

We investigate the size of habitat polygons for different species to identify species with the largest and smallest habitats. This helps in understanding habitat range and species' spatial requirements.
Global Habitat Visualization:

We visualize the habitat polygons on a global map, using a Mollweide projection. This provides an overview of global habitat distributions and helps in identifying regions of interest.
Local Habitat Visualization:

We zoom into specific regions to visualize habitat patches for selected species such as giraffes, gorillas, lions, and elephants. This detailed view helps in understanding species-specific habitat distributions.
Country-Based Mapping:

We aggregate habitat data by country to calculate the total number of species and endangered species per country. This information is visualized to highlight countries with high biodiversity and those facing significant conservation challenges.

**Requirements**

To run this project, you will need:

Python 3.x

GeoPandas

Matplotlib

Contextily

Pandas

Shapely


**Data Sources**
[IUCN Global Mammal Database][(([https://www.iucnredlist.org/resources/spatial-data-download](url)))](url)
[Natural Earth Admin 0 Countries][([(https://www.naturalearthdata.com/downloads/10m-cultural-vectors/)](url))](url)
