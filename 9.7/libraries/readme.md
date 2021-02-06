#Libraries

| Libraryname   | Description   |
| ------------- |:-------------:|
| uAddress      | Get an address and show it in a map. |
| uBank         | Bank functions. |
| uCollection   | Collection operation stuff. Such as totals. |
| uDate         | Date, time and calendar stuff. |
| uField        | Field specific behavior. |
| uFile         | Every possible file function we could think of. |
| uFolder 	| library wih default folder entries |
| <a name="uGeneral">uGeneral</a> | The function that contains a lot of general functionality. Such as errorhandling etc. |
| uHTML         | All the HTML functions we ever created are in here |
| uList         | Working with lists, all lists, even structs. |
| uMail         | Sending, receiving, validating email and loads of other stuff. |
| uLogin        | Login, register, forgot password and so on and so forth. |
| uNumeric      | Number functions. |
| uSort         | Sorting code library. |
| uString       | String library. |
| uStruct       | Struct library. |
| uTab          | Tab component specific library. |
| uXls14        | Microsoft Excel 14 library. |
| uXls15        | Microsoft Excel 15 library. |

##uAddress
##uBank
###constructIban - Construct the iban number
###getCheckDigit - Calculate the check digit
###charToValue - Convert an character to an IBAN value 


##uCollection
###COL_CALC_TOTAL
Calculate the totals of a record using a collection operation in the read trigger. 

##uDate
###getAge
###getWeekday

##uFile
###IP_GET_EXTENSION
Get the name of the file extension. Ie. TXT, XLS etc. 

##[link text](#uGeneral)uGeneral      

; one of the include procs
###ErrorHandling

; one of the include proc entries. 
####generalhandler
The standard clause if $status is negative then return $status. Otherwise continue.
mention the input parameters, the output parameters and a small text explaining what it does. 



##uHTML

##uList
###listToStruct


##uMail
###sendMail
###validateMail
###createMessage 
###addAttachment
###setNoReplyAddress		- works better in a component 
###sendNewsLetter 		- better in a component



##Login
##uNumeric
###maximum 
Determine the maximum value in a Uniface list 
###minimum 
Determine the minimum value in a Uniface list 

##uSort
##uString
##uStruct
##uTab
##uXls14
##uXls15






- create an anchor in the libraries table that moves to the ##item. Where a list can be found with the functions etc
- [link text](#abcd) should be an anchor that moves to the specific place
	- more on anchors here http://stackoverflow.com/questions/6695439/how-do-you-create-link-to-a-named-anchor-in-multimarkdown
