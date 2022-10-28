# Election Audit

Whenever there is a large amount of data, the gathering and processing of it has to be by means of a computer software, in this challenge we will be making use of Python as a tool to retrieve and display information for an Election Audit. Python, is a programming language that, in this particular case, will allow us to interact with the computer to retrieve and modify information from selected files.

## Overview

In an electoral process there should always be transparency in the results, in this case it needs to confirm the support of the different counties in the totality of the voting. With this, it is a way to corroborate the backing up of a candidate, where polls are usually made to the populations, and serves as a mean to legitimize or trust an election. 

One of the needs to generate a solution to analyze the results of an election with a large dataset, besides the time consuming, is to quickly give a result without involving much human error into it. The audit process will be made by taking into consideration the total votes for the elections, divided by counties, and the winner will be selected by the candidate with most approval. In this case the selection will consider the one with the most votes and the results will be saved in a text file.

## Election Results 

The script for this analysis starts in two parts, 'read' file part: by declaring all the variables that are going to store information from the CSV file and 'write': which is going to display and write the results in a '.txt' file. It has to be an iterative process (using the 'for' loop) to collect the votes and by applying conditionals ('if') to group and count for each candidate/county in the data. To read or save any information into a file, it was used the code imported from the CSV library, 'With open() as ():' and 'txt_file.write()', respectively. By running the code with python, it is seen all the information we need to answer a few questions. 

1. How many votes were cast in this congressional election?

A total of 369,711 total votes were cast in this election. 

2. The breakdown of the number of votes and the percentage of total votes for each county in the precinct is: 

- County votes:  
 - Jefferson: 10.5% (38,855)
 - Denver: 82.8% (306,055)
 - Arapahoe: 6.7% (24,801)

From this data it is clear that Denver was the county with the largest number of votes. 

3. Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

 - Charles Casper Stockham: 23.0% (85,213)
 - Diana DeGette: 73.8% (272,892)
 - Raymon Anthony Doane: 3.1% (11,606)

4. Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

                                                Winner: Diana DeGette
                                                Winning Vote Count: 272,892
                                                Winning Percentage: 73.8%

In the following image, it can be seen the display of the election results in the text file, making sure our code worked perfectly. 

![Election_Audit.png](/Resources/Election_Audit.png) 

## Summary 

There is a statement to the election commission that explores how this script can be used for any election, with two examples for modifying the script.


By analyzing the script, most of the process is made out of variables to get the information from the CSV file or to write the results to a new text file. 
This process is already automated taking into consideration this paths, which can certainly work only if a new CSV file correspond with similar pattern of data or at least the same tabular information used in this challenge. The path to save a file also could be different to not overwrite information and store for accountability's purpose. 

            ###Summary
            modifying: file_to_read from resources folder  
            modifying: file_to_save for analysis folder 
            
            
 Change counties for States?
 TYPE OF ELECTIONS Primary, Specials, Presidential.
