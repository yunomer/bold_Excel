# bold_Excel
A Python script that uses reads bold database links from an Excel file and looks up if there's a Wikipedia description available.
Currently it's not exactly bullet proof, so it needs special requirments for it to actually work.

Requirments:
1. The file name has to be in the same directory as the python script.
2. The name of the file has to be TAXDB_WebCrawling.xlsx
3. It has to be an Excel file (.xlsx)
4. The Program starts reading from Row 2 and reads columns B and D.
5. Column B (Or column 2) needs to contain the Taxon names. 
6. Column D (Or column 4) needs to contain the links to the Bold Database of the "Thing" in column B.

An Example of how it should look liks is:

tax.id	  tax.fk_tax_rank	      tax.taxon	Tax Brower URL
2	        2	Annelida	          http://boldsystems.org/index.php/Taxbrowser_Taxonpage?taxid=2
3	        2	Cnidaria	          http://boldsystems.org/index.php/Taxbrowser_Taxonpage?taxid=3
