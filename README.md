# ExcelToPDFConversion
This package is focusing on building a custom UiPath Activity that converts Excel File to PDF Document.
Converts a Worksheet in an Excel Workbook to an individual PDF File. If the Worksheet is left unspecified, the whole workbook is converted to PDF.


Input:

DestinationPath - Type String - Optional :
Specifies the absolute path of to store the PDF File.If unspecified, it takes in the path of the Source Excel File and stores the PDF File in that path.

ExcelSourcePath - Type String - Mandatory :
Specifies the absolute path of the excel file to be converted.

RemovePageBreaks - Type boolean - Mandatory :
Specifies whether page breaks in excel should be enabled or not.

SheetName- Type String - Optional :
Specifies the name of the particular sheet to be converted to PDF. If unspecified, the whole workbook is converted to a PDF Document.

Output:

result- Type boolean - Optional :
Returns True if the operation has been carried out successfully, otherwise returns False.


Follow the link to download the latest Nuget Package :
https://www.nuget.org/packages/ExceltoPDFConversionActivities/
