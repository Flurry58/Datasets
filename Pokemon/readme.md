About Dataset
Context

With the rise of the popularity of machine learning, this is a good opportunity to share a wide database of the even more popular video-game Pokémon by Nintendo, Game freak, and Creatures, originally released in 1996.

Pokémon started as a Role Playing Game (RPG), but due to its increasing popularity, its owners ended up producing many TV series, manga comics, and so on, as well as other types of video-games (like the famous Pokémon Go!).

This dataset is focused on the stats and features of the Pokémon in the RPGs. Until now (08/01/2017) seven generations of Pokémon have been published. All in all, this dataset does not include the data corresponding to the last generation, since 1) I created the databased when the seventh generation was not released yet, and 2) this database is a modification+extension of the database "721 Pokemon with stats" by Alberto Barradas (https://www.kaggle.com/abcsds/pokemon), which does not include (of course) the latest generation either.
Content

This database includes 21 variables per each of the 721 Pokémon of the first six generations, plus the Pokémon ID and its name. These variables are briefly described next:

    Number. Pokémon ID in the Pokédex.
    Name. Name of the Pokémon.
    Type_1. Primary type.
    Type_2. Second type, in case the Pokémon has it.
    Total. Sum of all the base stats (Health Points, Attack, Defense, Special Attack, Special Defense, and Speed).
    HP. Base Health Points.
    Attack. Base Attack.
    Defense. Base Defense.
    Sp_Atk. Base Special Attack.
    Sp_Def. Base Special Defense.
    Speed. Base Speed.
    Generation. Number of the generation when the Pokémon was introduced.
    isLegendary. Boolean that indicates whether the Pokémon is Legendary or not.
    Color. Color of the Pokémon according to the Pokédex.
    hasGender. Boolean that indicates if the Pokémon can be classified as female or male.
    Pr_male. In case the Pokémon has Gender, the probability of its being male. The probability of being female is, of course, 1 minus this value.
    Egg_Group_1. Egg Group of the Pokémon.
    Egg_Group_2. Second Egg Group of the Pokémon, in case it has two.
    hasMegaEvolution. Boolean that indicates whether the Pokémon is able to Mega-evolve or not.
    Height_m. Height of the Pokémon, in meters.
    Weight_kg. Weight of the Pokémon, in kilograms.
    Catch_Rate. Catch Rate.
    Body_Style. Body Style of the Pokémon according to the Pokédex.

Notes

Please note that many Pokémon are multi-form, and also some of them can Mega-evolve. I wanted to keep the structure of the dataset as simple and general as possible, as well as the Number variable (the ID of the Pokémon) unique. Hence, in the cases of the multi-form Pokémon, or the ones capable of Mega-evolve, I just chose one of the forms, the one I (and my brother) considered the standard and/or the most common. The specific choice for each of this Pokémon are shown below:

    Mega-Evolutions are not considered as Pokémon.
    Kyogre, Groudon. Primal forms not considered.
    Deoxis. Only normal form considered.
    Wormadam. Only plant form considered.
    Rotom. Only normal form considered, the one with types Electric and Ghost.
    Giratina. Origin form considered.
    Shaymin. Land form considered.
    Darmanitan. Standard mode considered.
    Tornadus, Thundurus, Landorus. Incarnate form considered.
    Kyurem. Normal form considered, not white or black forms.
    Meloetta. Aria form considered.
    Mewstic. Both female and male forms are equal in the considered variables.
    Aegislash. Shield form considered.
    Pumpkaboo, Gourgeist. Average size considered.
    Zygarde. 50% form considered.
    Hoopa. Confined form considered.

Acknowledgements

As said at the beginning, this database was based on the Kaggle database "721 Pokemon with stats" by Alberto Barradas (https://www.kaggle.com/abcsds/pokemon). The other resources I mainly used are listed below:

    WikiDex (http://es.pokemon.wikia.com/wiki/WikiDex).
    Bulbapedia, the community driven Pokémon encyclopedia (http://bulbapedia.bulbagarden.net/wiki/Main_Page).
    Smogon University (http://www.smogon.com/).

Possible future work

This dataset can be used with different objectives, such as, Pokémon clustering, trying to find relations or dependencies between the variables, and also for supervised classification purposes, where the class could be the Primary Type, but also many of the other variables.
Author

Asier López Zorrilla

LINK: https://www.kaggle.com/datasets/alopez247/pokemon
