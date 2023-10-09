# BioLink-3-User-Interface
  What is a BioLink 3 User Interface ? <br>
BioLink 3 User Interface is a program that brings data from the time attendance ( Suprema Device ) a text format <br>
to forward the information to third party program payroll and has functions to facilitate easy connection.


## Flow Diagram
The program will retrieve data through API and convert the data in json format to text file as we define and customize.

### Sequence Diagram
BioLink 3 User Interface Connect data via APi BioStar 2 <br>
![image](https://github.com/adisorncjame/BioLink-3-User-Interface/assets/62010897/afdf1c31-c2f5-4f05-a96f-dce7190bee27)

## Features
  - Dashboard Access Logs ( Real Time )
  - Manual Export Access Logs To Text File on Payroll Custom Format
  - Manual Export Access Logs To CSV File Support
  - Filter Frist In Last Out To Day
  - Text Alignment ( Left or Right )
  - Compensate for missing Text
  - Device Custom Fields
  - TNA Custom Fields
  - Upload FTP ( Fix Bugs )

### Features Third Party 
  - Settings Automatic Export Text File
  - Settings Automatic Tranfer File Protocol FTP or sFTP
    
## System Requirments
Basic specifications are based on The BioStar 2 Version

![image](https://github.com/adisorncjame/BioLink-3-User-Interface/assets/62010897/08fd4d2c-5c33-4743-b095-268382e8da4e)

### Operating System ( OS ) Support 
| Operating System | Support |
| ------------- | ------------- |
| Windows Server 2012 R2  | Out of Support |
| Windows Server 2016 | Support  |
| Windows Server 2022 | Support  |
| Windows 10 PRO | Support  |
| Windows 10 HOME | Support  |
| Windows 11 PRO | Support  |
| Windows 11 HOME | Support  |

# Formats
BioLink 3 User Interface Connect data via APi BioStar 2 <br>

### Syntax Formats
| Letters Format | Compensate Amount | Text Alignment | Compensate |
| ------------- | ------------- | ------------- | ------------- | 


#### Example 1 : 
I want to export userid by adding - to the missing data on the right, 10 Characters

##### Formats
| I | 10 | L | D |
| ------------- | ------------- | ------------- | ------------- | 
##### Data Example
| USERID | RESULT |
| ------------- | ------------- | 
| 444555 | ----444555 |
| 666777 | ----666777 |





### Compensate
| Letters | Export Value |
| ------------- | ------------- |
| W | White Space ( ) |
| U | Underscore (_) |
| D | Dash (-) |
| C | Comma (,) |
| E | Empty (Empty) |

### Text Alignment
| Letters | Export Value |
| ------------- | ------------- |
| L | Left |
| R | Right |


### Letters Formats
| Letters | Export Value |
| ------------- | ------------- |
| D | Datetime |
| Z | Datetime - 543 |
| I | User ID|
| J | Username |
| K | Usergroup |
| L | Device ID |
| N | Devices Name |
| O | Replace TNA Code from Map Settings|
| Q | Events Code |
| R | Events Name |
| S | Device Custom Fields 1 |
| T | Device Custom Fields 2 |
| U | Device Custom Fields 3 |
| V | Device Custom Fields 4 |
| A | User Custom Fields 1 |
| B | User Custom Fields 2 |
| C | User Custom Fields 3 |
| E | User Custom Fields 4 |
| F | User Custom Fields 5 |
| G | User Custom Fields 6 |
| H | User Custom Fields 7 |
| W | User Custom Fields 8 |
| X | User Custom Fields 9 |
| Y | User Custom Fields 10 |
| % | Aphabet Charset |






