# Uniface
Small titbits I developed over time for the Uniface development environment and ar now availiable in U9.7.05.

# Export File 

## Forms
| Filename | Description |
|--|--|
| CSV2JSON  | A component that extends on the DRAGNDROP component and turns a CSV file into a struct and then a JSON formatted string. |
| DRAGNDROP | A small component with a drag and drop implementation |

## Libraries
| Filename | Description |
| ------------- |:-------------:|
| [uAddress](#uAddress)       | Get an address and show it in a map. |
| [uBank](#uBank)             | Bank functions. |
| [uCollection](#uCollection) | Collection operation stuff. Such as totals. |
| [uDate](#uDate)             | Date, time and calendar stuff. |
| [uField](#uField)           | Field specific behavior. |
| [uFile](#uFile)             | Every possible file function we could think of. |
| [uFolder](#uFolder)         | library wih default folder entries |
| [uGeneral](#uGeneral)       | The function that contains a lot of general functionality. Such as errorhandling etc. |
| [uHTML](#uHTML)             | All the HTML functions we ever created are in here |
| [uList](#uList)             | Working with lists, all lists, even structs. |
| [uMail](#uMail)             | Sending, receiving, validating email and loads of other stuff. |
| [uLogin](#uLogin)           | Login, register, forgot password and so on and so forth. |
| [uNumeric](#uNumeric)       | Number functions. |
| [uSort](#uSort)             | Sorting code library. |
| [uString](#uString)         | String library. |
| [uStruct](#uStruct)         | Struct library. |
| [uTab](#uTab)               | Tab component specific library. |
| [uXls14](#uXls14)           | Microsoft Excel 14 library. |
| [uXls15](#uXls15)           | Microsoft Excel 15 library. |

## Signatures
| Filename | Description |
|--|--|
| xls14 | Generated signatures to connect to Microsoft Excel version 14 |
| xls15 | Generated signatures to connect to Microsoft Excel version 15 |

# Log
| Date | Description |
|--|--|
| 12-12-2020 | Added CSV2JSON and DRAGNDROP components  |
| 12-12-2020 | CSV2JSON update for U9.7.05 <br><ul><li>renamed the export filename</li><li>added some prechecking of the CSV file</li><li>added multiple seperator options (tab, comma, semicolon, other)</li><li>added option to select headers in the first line or no headers in the first line</li></ul> |
| 06-02-2021 | Reinstated the libraries and signatures folders |
