Example Files from PythonExcels
===============================

This repository contains example Python scripts described in the blog [http://www.pythonexcels.com/](http://www.pythonexcels.com).

add_a_workbook.py
-----------------

This script simply invokes Excel, adds a workbook and saves the empty workbook.

add_a_worksheet.py
------------------

This script creates a new Excel workbook with three sheets, adds a fourth worksheet, names it MyNewSheet and saves the workbook to the file add_a_worksheet.xlsx

autofill_cells.py
-----------------

This script uses Excels autofill capability to examine data in cells A1 and A2, then autofill the remaining cells through A10.  Excel spreadsheet is written to autofill_cells.xlsx.

cell_color.py
-------------

This script illustrates adding an interior color to the cell using Interior.ColorIndex.  Column A, rows 1 through 20 are filled with a number and assigned that ColorIndex.  The spreadsheet is written to cell_color.xlsx.

column_widths.py
----------------

This script creates two columns of data, one narrow and one wide, then formats the column width with the ColumnWidth property.  You can also use the Columns.AutoFit() function to autofit all columns in the spreadsheet.  The spreadsheet is written to column_widths.xlsx.

copy_worksheet_to_worksheet.py
------------------------------

This script uses FillAcrossSheets() to copy data from one location to all other worksheets in the workbook.  Specifically, the data in the range A1:J10 is copied from Sheet1 to Sheet2 and Sheet3.  The spreadsheet is written to copy_worksheet_to_worksheet.xlsx.

driving.py
----------

This is a simple introduction to opening Excel, creating a workbook, creating a worksheet and adding some data.  This script is best run by entering the text line-by-line into Python. A complete description of this script can be found at  [http://www.pythonexcels.com/2009/09/basic-excel-driving-with-python/](http://www.pythonexcels.com/2009/09/basic-excel-driving-with-python).  

format_cells.py
---------------

This script creates two columns of data, then formats the font type and font size used in the worksheet.  Five different fonts and sizes are used, the numbers are formatted using a monetary format.  The spreadsheet is written to format_cells.xlsx.

open_an_existing_workbook.py
----------------------------

This script opens an existing workbook and displays it (note the statement excel.Visible = True).  The file workbook1.xlsx would exist in the user's "My Documents" directory.  You can also open spreadsheet files by specifying the full path to the file as shown below.  Using r' in the statement r'C:\myfiles\excel\workbook2.xlsx' automatically escapes the backslash characters and makes the file name a bit more concise. 

ranges_and_offsets.py
---------------------

This script uses some different techniques for addressing cells using the <code>Cells()</code> and <code>Range()</code> operators. 

row_height.py
-------------

Similar to column height, row height can be set with the RowHeight setting.  You can also use <code>AutoFit()</code> to automatically adjust the row height based on cell contents.  

[pythonexcels]: http://www.pythonexcels.com
[python-excel]: http://www.python-excel.org
