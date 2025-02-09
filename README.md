# Tesco_Grocery_and_Educational_Attainment

## About the dataset:

The data is from : [Tesco Grocery 1.0](https://figshare.com/articles/dataset/Area-level_grocery_purchases/7796666?backTo=/collections/Tesco_Grocery_1_0/4769354)

The dataset contains records of 420 million food purchases made by 1.6 million Tesco loyalty card holders across 411 stores in Greater London for the year 2015. The data folder contains datasets containing the aggregated information on food purchases, enriched with information coming from the census for each geographic aggregation (LSOA, MSOA, Ward, Borough).

For this task we will look into the "year_borough_grocery.csv" dataset. <mark> MENTION WHY </mark>

<b> The Columns of the Dataset </b>

- area_id: identifier of the area
- weight: Weight of the average food product, in grams
- volume: Volume of the average drink product, in liters
- energy: Nutritional energy of the average product, in kcals
- energy_density: Concentration of calories in the area's average product, in kcals/gram
- {nutrient}: Weight of {nutrient} in the average product, in grams. Possible nutrients are: carbs, sugar, fat, saturated fat, protein, fibre. The count of carbs include sugars and the count of fats includes saturated fats
- energy\_{nutrient}: Amount of energy from {nutrient} in the average product, in kcals
- h_nutrients_weight: Diversity (entropy) of nutrients weight
- h_nutrients_weight_norm: Diversity (entropy) of nutrients weight, normalized in [0,1]
- h_nutrients_calories: Diversity (entropy) of energy from nutrients
- h_nutrients_calories_norm. Diversity (entropy) of energy from nutrients, normalized in [0,1]
- f\_{category}: Fraction of products of type {category} purchased. Possible categories are: beer, dairy, eggs, fats & oils, fish, fruit & veg, grains, red meat, poultry, readymade, sauces, soft drinks, spirits, sweets, tea & coffee, water, and wine.
- f\_{category}\_weight: Fraction of total product weight given by products of type {category}
- h_category: Diversity (entropy) of food product categories
- h_category_norm: Diversity (entropy) of food product categories, normalized in [0,1]
- h_category_weight: Diversity (entropy) of weight of food product categories
- h_category_weight_norm: Diversity (entropy) of weight of food product categories, normalized in [0,1].
- representativeness_norm: The ratio between the number of unique customers in the area and the number of residents as measured by the census; values are min-max normalized in [0,1] across all areas
- transaction_days: Number of unique dates in which at least one purchase has been made by one of the residents in the area.
- num_transactions: Total number of products purchased by Clubcard owners who are resident in the area.
- man_day: Cumulative number of man-days of purchase (number of distinct days a customer has purchased something, summed all individual customers)
- population: Total population of residents in the area according to the 2015 census.
- male: Total male population in the area.
- female: Total female population in the area.
- age_0_17: Total number of residents between 0 and 17 years old
- age_18_64: Total number of residents between 18 and 64 years old.
- age_65+: Total number of residents aged 65 years or more.
- avg_age: Average age of residents according to the 2015 census
- area_sq_km: Surface of the area (km^2)
- people_per_sq_km: Population density per km^2
