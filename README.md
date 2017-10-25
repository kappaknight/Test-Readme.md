# Python Calender Functions
##### Version: v0.21 date 24-10-2017
## Functions
### getDateTime()
> This function gets the actual date and time, based on the systems clock <br />
> There are no arguments to put in <br />
> The function returns the actual year, the actual month, the actual day, the actual hour, the actual minute and the actual second, all as integer values <br />
> Example to use:  `year, month, day, hour, minute, second = getDateTime()` <br />
### getDowStr()
> This function gets the day of the week as a string <br />
> Inputs arguments are the year, the month and the day <br />
> The function returns the day of the week as a string (Monday ... Sunday)<br />
> Example to use: `dowStr = getDowStr(year, month, day)` <br />
### getDowNr()
> This function gets the actual day of the week as an integer <br />
> Input argument is the  actual day of the week as a string <br />
> The function returns the day of the week as an integer (1 ... 7 where 1 is Monday and 7 is Sunday) <br />
> Example to use: `dowNr = getDowNr(dowStr)` <br />
### getWeekNr()
> This function gets the actual week number as an integer <br />
> Input arguments are year, month and day as integers <br />
> The function returns the actual week number of the year as an integer (1...53) <br />
> Example to use: `weekNr = getWeekNr (year, month, day)` <br />
### ifLeapYear()
> This function checks if the year is a leap year and returns a bolean <br />
> Input argument is the year to check as an integer <br />
> The function return True if the year is a leap year, else it returns False<br />
> Example to use: `leapYear = ifLeapYear(year)` <br />
### getDOYNr()
> This function returns the day number of the year as an integer <br />
> Inputs arguments are the year, the month and the day <br />
> The function returns the actual day number of the year as an integer (1...366) <br />
> Example to use: `doy = getDOYNr(year, month, day)` <br />
