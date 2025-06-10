### Datasets
For this assessment you have been provided a single dataset, `gourds.csv`. This dataset contains the results of the Great Pumpkin Commonwealth Weighoff for the years 2013 through 2021. The columns of this dataframe are contained in the data dictionary.md file.

### Instructions
1. Create a Jupyter notebook and name it <firstname_gourds>. For example, John Smith's notebook would be named `john_gourds.ipynb`
2. Read in the gourds data into a DataFrame named `gourds` and look at the top 5 rows.
3. Create a visualization (your choice) which shows the distribution of weights across the dataset. What do you notice from this visualization?
4. The place column contains the finishing position of a gourd within its category for a given year. Convert this column to a numeric type. (Note: this column contains two non-numeric values - 'EXH' and 'DMG'. You can replace these values with NaN.). If you cannot find a solution for this question, you can use the `place_bk` column in order to answer the questions that follow that rely on it.
5. Which country shows up the most frequently in the dataset? Create a visualization (your choice) to show the frequency of appearances for the top 5 countries in terms of number of appearances.
6. The `id` column contains contains a concatenation of the year and an abbreviation for the type of gourd. For example "2013-F" means that this record is from the year 2013, and the gourd is of type "F" (which stands for Field Pumpkin). Create two new columns, `year` and `type` by extracting these values from the `id` column. If you cannot find a solution for this question, you can use the `year_bk` and `type_bk` columns to answer the questions below that rely on it.
7. Create a line plot showing the trend in the **heaviest** gourd by year. What do you notice?
8. Replace the type abbreviations with the full names of each type. 
    ```
    "F": "Field Pumpkin"
    "P": "Giant Pumpkin"
    "S": "Giant Squash"
    "W": "Giant Watermelon"
    "T": "Tomato"
    "L": "Long Gourd"
    ```
    Which type of gourd is heaviest on average? Create a visualization showing the distribution of gourd weights by type.

9. Create a visualization to compare the estimated weight (`est_weight`) to the actual weight (`weight_lbs`). What do you notice?
10. Create a new column `weight_error` that contains the amount by which the estimated weight exceeded the actual weight. What is the worst overestimate of a gourd weight? What percentage of gourd weights are overestimated?
11. Some growers compete across multiple types of gourd. Which grower has **top 10** finishes across the largest number of types of gourds? What is this grower's best finish in the GPC Weighoff in the years that are covered in this dataset?
12. How many gourds have at least 100 offspring that have appeared in the GPC Weighoff? You can count a pumpkin as having an offspring if it is either the seed_mother or pollinator_father. Hint: One way you could do this is to create two `value_counts` Series on the `seed_mother` and `pollinator_father` columns and merge them.