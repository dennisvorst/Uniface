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
#### Operations 
| Name   | Description   |
| COL_CALC_TOTAL | Calculate the totals of a record using a collection operation in the read trigger. |

### uDate
#### Operations 
#### Entries
| Name   | Description   |
| getAge | |
| getWeekday | |
| IP_MOVE_ELEMENT | |
| IP_SET_SELECTION | |

### uFile
#### Operations 
#### Entries
| Name   | Description   |
| IP_ADD_SLASH | |
| IP_CRE_FOLDER | |
| IP_CRE_FOLDERNM | |
| IP_FOLDEREXISTS | |
| IP_GET_EXTENSION | Get the name of the file extension. Ie. TXT, XLS etc. |
| IP_GET_SLASHES | |
| IP_REPLACE_SEPERATOR | |
| IP_REP_SEPERATOR | |

### uFolder
#### Operations 
#### Entries
| Name   | Description   |
| IP_FILTER_EXT | |
| IP_GET_FOLDERCONTENT | |
| IP_LIST_FILES | |
| IP_LIST_FOLDERS | |

### uGeneral
#### Operations 
| Name   | Description   |
| IO_ADD_RECORD | |

#### Entries
| Name   | Description   |
| ErrorHandling | |
| IP_CHECK_ALL | |
| IP_SELECTALL | |

### uHTML
#### Operations 
#### Entries
| Name   | Description   |
| createHtml | |
| createInputField | |

### uList
#### Operations 
#### Entries
| Name   | Description   |
| listToStruct | |
| IP_ADD_KEYS2LIST | |
| IP_COUNT_VALUES | |
| IP_IS_LIST | |
| IP_MERGE_LIST | |
| IP_MIX_MATCH | |
| IP_PURGE_LISTITEMS | |
| IP_REM_BLANKS | |
| IP_SPLIT_LIST | |
| IP_STRING_LIST | |
| IP_TRIM_LISTITEMS | |
| IP_TRIM_LIST | |

### Login
#### Operations 
#### Entries


### uMail
#### Operations 
#### Entries
| Name   | Description   |
| sendMail | |
| validateMail | |
| createMessage  | |
| addAttachment | |
| setNoReplyAddress | works better in a component |
| sendNewsLetter  | better in a component |

### uNumeric 
#### Operations 
#### Entries
| Name   | Description   |
| maximum | Determine the maximum value in a Uniface list |
| minimum | Determine the minimum value in a Uniface list |
| alphabet2Number | |
| ascii2Char | |
| char2Ascii | |

### uSort

### uString
todo: what is the difference between string2lsit and stringlist
#### Operations 
#### Entries
| Name   | Description   |
| checkCase | |
| countString | |
| cutString | |
| getLocations | |
| get_Levenshtein | |
| list2String | |
| number2Alphabet | |
| replaceAll | |
| string2List | |
| stringList | |


### uStruct
todo: copystruct defined twice, find out why 
#### Operations 
#### Entries
| Name   | Description   |
| copyStruct | |
| copyStruct | |
| getDeepestChild | |
| getStruct | |
| hasStructCollValues | |
| isStructCollItemValue | |
| structExists | |
| structIsEmpty | |

### uTab
#### Operations 
| Name   | Description   |
| IO_DO_ACCEPT | |
| IO_DO_CLEAR | |
| IO_DO_QUIT | |
| IO_DO_STORE | |
| IO_GET_MODSTATE | |

#### Entries
| Name   | Description   |
| IP_ACTIVATE_TAB | |
| IP_DEL_TAB_INST | |
| IP_GET_PK | |
| IP_INIT_TAB | |
| IP_SET_TAB | |


### uXls14
Library for Microsoft Excel version 14: https://nl.wikipedia.org/wiki/Microsoft_Excel 
#### Operations 
#### Entries
| Name   | Description   |
| checkVersion | |
| column2Number | |
| delApplication | |
| delWorkbooks | |
| getActivecell | |
| getActivesheet | |
| getApplication | |
| getCellValues | |
| getEmptyColumn | |
| getEmptyRow | |
| getFilename | |
| getFileTypes | |
| getTabname | |
| getTabNames | |
| getValue | |
| getWorkbook | |
| getWorkbooks | |
| gotoFirstTab | |
| gotoLastTab | |
| gotoNamedTab | |
| number2Column | |
| openWorkbook | |
| setFormulaR1C1 | |
| setTabname | |
| setValue | |
| setVisible | |

### uXls15
Library for Microsoft Excel version 14: https://nl.wikipedia.org/wiki/Microsoft_Excel 
todo: why did I not keep the names the same?

#### Operations 
#### Entries
| Name   | Description   |
| CHECK_VERSION | |
| column2Number | |
| DEL_APPLICATION | |
| DEL_WORKBOOKS | |
| getFileTypes | |
| GET_ACTIVECELL | |
| GET_ACTIVESHEET | |
| GET_APPLICATION | |
| GET_CELLVALUES | |
| GET_EMPTYCOLUMN | |
| GET_EMPTYROW | |
| GET_FILENAME | |
| GET_TABNAME | |
| GET_TABNAMES | |
| GET_VALUE | |
| GET_WORKBOOK | |
| GET_WORKBOOKS | |
| GOTO_FIRSTTAB | |
| GOTO_LASTTAB | |
| GOTO_NAMEDTAB | |
| number2Column | |
| OPEN_WORKBOOK | |
| setValue | |
| SET_FORMULAR1C1 | |
| SET_TABNAME | |
| SET_VISIBLE | |