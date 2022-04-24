# CDP-Guidance-Documents-AutoDownloader
![image](https://user-images.githubusercontent.com/23148033/155912669-e9f1adc8-7e0b-4b13-a377-ad71defb9bcb.png)
This tool automatically exports CDP Questionnaire, Reporting Guidance and Scoring Methodology documents for all sectors and the three themes of Water Security, Forests and Climate Change and also the Question Level Guidance for the Climate Change theme.

Steps to run program:
1. Create a Firefox profile which has Download Action for PDF files as "Save File". This is because Selenium can not auto-click options in the download pop-up (or I couldn't find one). Reference the path to this profile in the code.
2. Install all packages mentioned in the Python Notebook.
3. Adjust sleep times as needed.
4. Wait as all Guidance Documents are exported to PDF in the default download directory.
