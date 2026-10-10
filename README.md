# Tuka Layout to Excel

Turns Tukatech marker layout PDFs into the JC consumption sheet (.xlsx).

**Use it:** https://dkcvivek.github.io/tuka-layout-to-excel/

1. Drop one or more marker PDFs on the page.
2. Check the style name, JC number and fabric (they are read from the file name and can be edited).
3. Download the .xlsx. Files are named `JC<number>_<name>_extracted.xlsx`.

The sheet holds date, time, file, fabric, total and placed parts, pieces (bundles), efficiency, width, length and yield in metres, and consumption per piece (yield ÷ pieces) as a live formula.

PDFs are read in the browser and never uploaded. The page loads the PDF reader (pdf.js) from cdnjs, so it needs an internet connection.
