# Auto Billing

## Introduction

This program is made to assist the process of identifying students that require to be charged a full day surchage

## How it works

1. Read the spreadsheet
2. Loop through each student in the spreadsheet, find their sign-in and sign-out timings based on the given columns
3. Highlight the cells for the days that the student stayed for the whole day in a certain color (default is `FFFF00`)
4. Fill in the number of days to be charged for each student by counting the number of cells in the row that are highlighted with said color (This is to ensure that cells that have already been manually highlighted will not be counted twice)
5. Save the new edited spreadsheet in a new file (default file name is `test_highlight.xlsx`)

## Extra points

-   Because the program is written using `pynb`, the functions for auto highlighting and counting can be run independently, allowing users to use the program to either automate the process or check their work.
-   This program is still in it's experimental phase, please double check the work done as bugs may occur

## How to use

1. You may edit the fields in the second section labelled `Customize Variables`. Variables are explained in (Insert Section)
2. Click on the `Run all` button
