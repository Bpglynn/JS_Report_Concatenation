# JS_Report_Concatenation

A simple Javascript/HTML file I made for my wife to help her do monthly report processing more easily. She gets a formatted report file for every day of a given month that contains cover and trailer pages and detail records formatted in a human-readable format when what she really wants is the detail records as individual rows in an Excel spreadsheet.

This utility will accept multiple files and pull out detail records into a comma seperated value list that can be copy/pasted into Excel. The reports are in a fixed format so this is done using offsets after locating the report name within each file.

THe included file01.txt, file02.txt, and file03.txt files simulate the report format using dummy data and are included for demonstration and/or experimentation.