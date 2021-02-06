# Libraries
This section contains a collection of libraries.

## Installation

Import the export file directly into your development enviornment or from the commandline use:

```bash
/imp uAddress.xml
```

## Usage
tbd

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
tbd

## Content

| Libraryname   | Description   |
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

### uAddress
### uBank
#### constructIban - Construct the iban number
#### getCheckDigit - Calculate the check digit
#### charToValue - Convert an character to an IBAN value 


### uCollection
#### COL_CALC_TOTAL
Calculate the totals of a record using a collection operation in the read trigger. 

### uDate
#### getAge
#### getWeekday

### uFile
#### IP_GET_EXTENSION
Get the name of the file extension. Ie. TXT, XLS etc. 

### uGeneral

; one of the include procs
#### ErrorHandling

; one of the include proc entries. 
##### generalhandler
The standard clause if $status is negative then return $status. Otherwise continue.
mention the input parameters, the output parameters and a small text explaining what it does. 



### uHTML

### uList
#### listToStruct


### uMail
#### sendMail
#### validateMail
#### createMessage 
#### addAttachment
#### setNoReplyAddress		- works better in a component 
#### sendNewsLetter 		- better in a component


### Login

### uNumeric
#### maximum 
Determine the maximum value in a Uniface list 
#### minimum 
Determine the minimum value in a Uniface list 

### uSort

### uString

### uStruct

### uTab

### uXls14

### uXls15

