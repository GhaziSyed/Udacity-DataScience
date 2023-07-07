
# Pokémon Analysis

<center>
    <img src="./preview.jpg" alt="Preview" width="500"/>
</center>

As a developer at pokémonunleashed.org, your responsibility is to develop an interactive Python script for your board members. These members, just like you, have a strong passion for the Pokémon world. To accomplish this task, you will be following the CRoss Industry Standard Process for Data Mining (CRISP-DM) methodology. 

For this, you have done your research and broken down the process for this task as follows:

- **Business understanding:** 
  The business requires a Python script that can interact with the Pokémon dataset and PokeAPI to enable users to ask various questions.

- **Data understanding:**
  The Pokémon dataset is a CSV file with 13 fields/attributes.

- **Data preparation:**
  The dataset is to be loaded into a dataframe, and irrelevant columns are to be removed.

- **Modeling:**
  The data must be analyzed for correlations, and a regression fit is performed between the correlated traits.

**Files**:

- `Pokemon_Analysis.ipynb`: This is a Jupyter Notebook which contains the main script and is executed for analysis.
- `Pokemon.csv`: This is the dataset file which is loaded in `Pokemon_Analysis.ipynb`.
- `Pokemon_names.xlsx`: This file lists all the names of the Pokémon, which are accessed through PokeAPI.

**Execution**:

When pokemon_Analysis.ipynb is executed, the following actions take place:

- The dataset is loaded and converted into a dataframe.
- The dataframe is curated to include only the necessary entries for analysis.
- Various plots and visualizations are generated to provide insights into the dataset.
- Based on user queries, the script can answer questions related to the dataset.
- Additionally, the script has the capability to retrieve photographs of Pokémon from the internet using a RESTful API.

For further reading, refer to the post on [Medium](https://medium.com/@syedghazisarwat/a-simple-analysis-of-pok%C3%A9mon-exploring-the-pok%C3%A9mon-world-with-python-b60bae7ca8e5)

