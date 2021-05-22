# [Pokemon_Data_Analysis](https://github.com/Deepakit/Pokemon_Data_Analysis/blob/master/Untitled.ipynb)

Pokemon is a global icon to children and adults everywhere. It is a TV series that has expanded into video games, card games, movies, merchandise and everything inbetween. The motivation behind this analysis is to further understand the dynamics of the pokemon universe through data.

Aim is to analyse the data and find patterns in it like which is the weakest type/generation of pokemon. Is there a relation between body measurement and strength of pokemon.

Standar Procedure is followed in the notebook for the analysis:
1) Importing data
2) Looking at data definition and descriptive statistics.
3) Handling of Missing Values
4) Outliers
5) Exploratory Data Analysis

# Data Definition:
We have total of 801 entries of different Pokemon.
* name: The English name of the Pokemon
* japanese_name: The Original Japanese name of the Pokemon
* pokedex_number: The entry number of the Pokemon in the National Pokedex
* percentage_male: The percentage of the species that are male. Blank if the Pokemon is genderless.
* type1: The Primary Type of the Pokemon
* type2: The Secondary Type of the Pokemon
* classification: The Classification of the Pokemon as described by the Sun and Moon Pokedex
* height_m: Height of the Pokemon in metres
* weight_kg: The Weight of the Pokemon in kilograms
* capture_rate: Capture Rate of the Pokemon
* baseeggsteps: The number of steps required to hatch an egg of the Pokemon
* abilities: A stringified list of abilities that the Pokemon is capable of having
* experience_growth: The Experience Growth of the Pokemon
* base_happiness: Base Happiness of the Pokemon
* against_?: Eighteen features that denote the amount of damage taken against an attack of a particular type
* hp: The Base HP of the Pokemon
* attack: The Base Attack of the Pokemon
* defense: The Base Defense of the Pokemon
* sp_attack: The Base Special Attack of the Pokemon
* sp_defense: The Base Special Defense of the Pokemon
* speed: The Base Speed of the Pokemon
* generation: The numbered generation which the Pokemon was first introduced
* is_legendary: Denotes if the Pokemon is legendary.

# Distribution
Plotted a category plot for all pokemon's and their generation.
![]
