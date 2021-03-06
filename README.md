# Relic Valuation

This script is all about Warframe and automating some basic tasks related to the game. Trying to value relics in warframe currently needs you to:
* Get the relic you want
* Find out it's rare drop
* Go to warframe.market and search its rare drop. 

This is cumbersome and thus I have automated the process of looking up the value for each relic. This project was undertaken using Google Sheets and this is simply a dump for the code used since I am too lazy to publish.

## Example
[Warframe Relic Values](https://docs.google.com/spreadsheets/d/135-Dbjjcd8f4eOiy2vyKLhfGKhtg1PaNDMVsGm7IpVA/edit?usp=sharing)

## Getting Started

* Make new Google Sheet
* Go to tools > script editor
* Paste code from valueRelic.js
* Go back to sheet and fill in a relics name and rare item drop
* In a separate cell use =valueitem(the_cell)

## Prerequisites

Google Sheets.

## Setting up a Spreadsheet
* Follow getting started section
* Create sheets with the same names and layout as shown: (conditional formatting optional)
![image not found](images/TableTemplate3.png)
* Go to Tools/Script Editor, Select function/setUpSpreadsheet
* Run selected function

## Valuing an Item
After laying out my table as shown above, in the first cell of the "Min Sell" column I put:

![image not found](images/valueItem.png)

And then double-clicked the bottom corner of the cell to fill out all the rest

![image not found](images/cursor.png)
