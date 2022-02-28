# CDP-Guidance-Documents-AutoDownloader
This tool automatically exports CDP Questionnaire and Reporting Guidance documents for all sectors and the three themes of Water Security, Forests and Climate Change (Scoring Methodology downloading will be added soon).

Steps to run program:
1. Create a Firefox profile which has Download Action for PDF files as "Save File". This is because Selenium can not auto-click options in the download pop-up (or I couldn't find one). Reference the path to this profile in the code.
2. Install all packages mentioned in the Python Notebook.
3. Adjust sleep times as needed.
4. Wait as all Guidance Documents are exported to PDF in the default download directory.
