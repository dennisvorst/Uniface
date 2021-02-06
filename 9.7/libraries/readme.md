# Libraries
This section contains a collection of libraries, that all 

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
| <a name="uAddress">uAddress</a>       | Get an address and show it in a map. |
| <a name="uBank">uBank</a>             | Bank functions. |
| <a name="uCollection">uCollection</a> | Collection operation stuff. Such as totals. |
| <a name="uDate">uDate</a>             | Date, time and calendar stuff. |
| <a name="uField">uField</a>           | Field specific behavior. |
| <a name="uFile">uFile</a>             | Every possible file function we could think of. |
| <a name="uFolder">uFolder</a>         | library wih default folder entries |
| <a name="uGeneral">uGeneral</a>       | The function that contains a lot of general functionality. Such as errorhandling etc. |
| <a name="uHTML">uHTML</a>             | All the HTML functions we ever created are in here |
| <a name="uList">uList</a>             | Working with lists, all lists, even structs. |
| <a name="uMail">uMail</a>             | Sending, receiving, validating email and loads of other stuff. |
| <a name="uLogin">uLogin</a>           | Login, register, forgot password and so on and so forth. |
| <a name="uNumeric">uNumeric</a>       | Number functions. |
| <a name="uSort">uSort</a>             | Sorting code library. |
| <a name="uString">uString</a>         | String library. |
| <a name="uStruct">uStruct</a>         | Struct library. |
| <a name="uTab">uTab</a>               | Tab component specific library. |
| <a name="uXls14">uXls14</a>           | Microsoft Excel 14 library. |
| <a name="uXls15">uXls15</a>           | Microsoft Excel 15 library. |

### [link text](#uAddress)uAddress
### [link text](#uBank)uBank
#### constructIban - Construct the iban number
#### getCheckDigit - Calculate the check digit
#### charToValue - Convert an character to an IBAN value 


### [link text](#uCollection)uCollection
#### COL_CALC_TOTAL
Calculate the totals of a record using a collection operation in the read trigger. 

### [link text](#uDate)uDate
#### getAge
#### getWeekday

### [link text](#uFile)uFile
#### IP_GET_EXTENSION
Get the name of the file extension. Ie. TXT, XLS etc. 

### [link text](#uGeneral)uGeneral      

; one of the include procs
#### ErrorHandling

; one of the include proc entries. 
##### generalhandler
The standard clause if $status is negative then return $status. Otherwise continue.
mention the input parameters, the output parameters and a small text explaining what it does. 



### [link text](#uHTML)uHTML

### [link text](#uList)uList
#### listToStruct


### [link text](#uMail)uMail
#### sendMail
#### validateMail
#### createMessage 
#### addAttachment
#### setNoReplyAddress		- works better in a component 
#### sendNewsLetter 		- better in a component



### [link text](#Login)Login
### [link text](#uNumeric)uNumeric
#### maximum 
Determine the maximum value in a Uniface list 
#### minimum 
Determine the minimum value in a Uniface list 

### [link text](#uSort)uSort
### [link text](#uString)uString
### [link text](#uStruct)uStruct
### [link text](#uTab)uTab
### [link text](#uXls14)uXls14
### [link text](#uXls15)uXls15
