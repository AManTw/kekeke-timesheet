# kekeke-timesheet

License: [Beerware](https://zh.wikipedia.org/wiki/%E5%95%A4%E9%85%92%E8%BB%9F%E9%AB%94)

## HOW TO USE

1. clone the utils

		git clone https://github.com/AManTw/kekeke-timesheet.git
		cd kekeke-timesheet/

2. syntax
		1)Editting the project_name, bu, task_item to yours
		
		2)
		$ ./gen_timesheet2.sh [the month you want]
		ex: $ ./gen_timesheet2.sh 4    # use April
		ex: $ ./gen_timesheet2.sh      # use current month

3. it will generate a .xlsx file.

		ex: timesheet-4.xlsx           # '-4' means for April

4. login to Time System

5. select the month you want to upload

6. click "Import-2" to import the .xlsx file we creted

Warning: 

	'ONLY ONE' data field will be generated in the timesheet.
	Because I am lazy to improve it :-p
	Don't try to improve this code!
	Because if you have time to do that, it's better to write a complete timesheet XD
