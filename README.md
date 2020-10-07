# Heroes of Pymoli
> This challenge involves analyzing the data for fantasy game Heroes of Pymoli. 

## General info
Heroes of Pymoli has input dataset in .csv format & has over 1000 records. The goal is to analyze players' purchasing patterns based on gender, age, popularity of the items bought & profitablity of the items.

## Screenshots
![Example screenshot](./img/screenshot.png)

## Technologies
* conda - version 4.8.3
* jupyter notebook - version 6.0.3

## Code Examples
I approached this by first opening and reviewing the dataset in VS code & excel. I went through each ask & filtered/sorted through excel to understand what was expected.
This helped me break it down & go to instruction recordings/google to review while implementing. The comments have been included in the code & here are some key takeaways:

`Purchasing Analysis:
-used pd.options.display.float_format to format the floats. This gave me the answer in cleaner format.
 
 Gender Demographics:
 -used .map function - mapped dataframe column values with dictionary key - decimal & % format.
 
 Purchasing Analysis(Gender):
 -used reset_index() to 'align' the column names in the o/p dataframe.
 
 Age Demographics & Purchasing Analysis:
 -applied binning. These are tricky.Took a while to narrow down the duplicates from sliced data!
 
 Top Spenders & Most Popular Items:
 -pd.merge!! this took a while to implement. Some interesting reads on merges/joins helped.
 `
## Inference from Analysis
 The following key trends were observed:
-Males spent more money on purchasing items than females.
-There are many closely popular items.


## Reading references
Some helpful google reading references:
https://kanoki.org/2019/04/06/pandas-map-dictionary-values-with-dataframe-columns/
https://www.geeksforgeeks.org/how-to-join-pandas-dataframes-using-merge/


