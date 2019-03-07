# DATABANK

Team Asia's repository for everything data related

## A guide through the datasets
There are two sets of data:
* sample_datasets
* real_datasets

We will be dealing more with the datasets on `real_datasets`.\
**This is how you identify the datasets**:

1. Open up `guide.xlsx`, Which is the guide for the folder `/real_datasets`.
2. There will be 5 groups columns. `[A, B], [D, E], [G, H], [I, J], [M, N]`
3. 
    * The bolded numbers that ranges from 1 to 138 are the **sheet numbers**. 
    * The italic numbers were the **last 5 numbers of the corresponding csv file.**\
    **Example**: Column E3 gives *sheet number 136*, and the corresponding file have the last 5 numbers *55240*. (In this case, `Sheet_2019022513255240.csv`) 

## Special notes on the datasets
* **dud**: The sheet went awry and we throw them away
* **DEAD**: The sensors stops reading the sheet
* **skewed**: The sheet has significant skew that might affect the quality of the data.

### /version_cole:
Cole seperated the sheets into training and testing and put them in their respective folders

### /version_yuka:
Building up from what Cole had done, Yuka renamed all the sheets as the actual sheet names so that the script to create an SQL file can be written more easily. (This is a temporary measure.)