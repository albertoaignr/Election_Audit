# Election Audit

Whenever there is a large amount of data, the gathering and processing of it has to be by means of a computer software, in this challenge we will be making use of Python as a tool to retrieve and display information for an Election Audit. Python, is a programming language that, in this particular case, will allow us to interact with the computer to retrieve and modify information from selected files.

## Overview

In an electoral process there should always be transparency in the results, in this case it needs to confirm the support of the different counties in the totality of the voting. With this, it is a way to corroborate the backing up of a candidate, where polls are usually made to the populations, and serves as a mean to legitimize or trust an election. 

One of the needs to generate a solution to analyze the results of an election with a large dataset, besides the time consuming, is to quickly give a result without involving much human error into it. The audit process will be made by taking into consideration the total votes for the elections, divided by counties, and the winner will be selected by the candidate with most approval. In this case the selection will consider the one with the most votes and the results will be saved in a text file.

## Results 

It all started with the data analysis, where 

In the following image it can be seen the display of the election results in a diferent tab once we run our code, divided by counties, votes and votes percentage. Also, the county with most votes and the overall candidate winner.

![Election_Audit.png](/Resources/Election_Audit.png)

From it we can say the data has been counted and congratulations will be given to the winner candidate, Diana DeGette. Though all the votes weren't from Denver county, she had a lot of support from it. 

## Summary 

There is a statement to the election commission that explores how this script can be used for any election, with two examples for modifying the script.


By analyzing the script, most of the process is made out of variables to get the information from the CSV file or to write the results to a new text file. 
This process is already automated taking into consideration this paths, which can certainly work only if a new CSV file correspond with similar pattern of data or at least the same tabular information used in this challenge. The path to save a file also could be different to not overwrite information and store for accountability's purpose. 

            modifying: file_to_read from resources folder  
            modifying: file_to_save for analysis folder 
