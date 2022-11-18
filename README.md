# PokeGraph

## Mission:
PokeGraph was created with the intent of analyzing the numerous different Pokemon featured in the titular video game series. Specifically, this version of Pokegraph analyzes the typings and secondary typings of the original 151 Pokemon featured in 1998's Pokemon Red Version and Pokemon Blue Version. To achieve this, a custom made excel file featuring the names of the Pokemon, the primary typings, and the secondary typings is read into the program. With this data, multiple math equations are proposed and answered, including the total number of Pokemon with secondary types, the average number of Pokemon belonging to each type, and the most frequent number of Pokemon belonging to individual types. After these equations, the total number of each type is compared against each other in the form of two distinct bar graphs, one for primary types and one for secondary types.

## Necessary Packages:
pip install pandas
pip install matplotlib
pip install numpy
pip install openpyxl

## Featured Features:
1. Read Data In: For this feature, I read in data from an excel file that I made myself. Initially, I had planned to use an API to pull data in but decided that the excel route was more suited to this project.
2. Manipulate and Clean Your Data: For this feature, I utilized a built-in Pandas function to recognize null values in the dataset and have the program recognize them as if they were a defined piece of data.
3. Analyze Your Data: For this feature, I used basic Pandas calculations to find different statistics about my data. There are eight calculations in total.
4. Visual Your Data: For this feature, I made two basic bar graphs with matplotlib that compared the total number of Pokemon belonging to each unique type and each unique secondary type.
5. Interpret Your Data: For this feature, I wrote markdown cells in my Jupyter Notebook explaining my thought process and code. 
