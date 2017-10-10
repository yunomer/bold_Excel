# bold_Excel
A Python script that uses bold database links from an Excel file and looks up if there's a Wikipedia description available.
Currently it's not exactly bullet proof, so it needs special requirments for it to actually work.

Using libraries: Openpyxl and beautifulsoup4

Requirments:
1. The file name has to be in the same directory as the python script.
2. The name of the file has to be TAXDB_WebCrawling.xlsx
3. It has to be an Excel file (.xlsx)
4. The Program starts reading from Row 2 and reads columns B, C and D.
5. Column B (Or column 2) needs to contain the Taxon ranks. 
6. Column C (Or column 3) needs to contain the Taxon names.
6. Column D (Or column 4) needs to contain the links to the Bold Database.

An Example of how it should look liks is provided in the Excel file on this repo.
