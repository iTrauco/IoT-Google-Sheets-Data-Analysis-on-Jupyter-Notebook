# IoT - Google Sheets Data Analysis on Jupyter Notebook

1. Open https://console.developers.google.com/

2. Login using your gmail account

3. Click on drop down as shown in following image 

![alt text](https://github.com/techtutorials/IoT-Google-Sheets-Data-Analysis-on-Jupyter-Notebook/blob/master/images/google1.png "Help Image 1")

4. A pop up will open. On the top right of pop up, click on "New Project"

![alt text](https://github.com/techtutorials/IoT-Google-Sheets-Data-Analysis-on-Jupyter-Notebook/blob/master/images/google2.png "Help Image 2")

5. Give a project name as shown in the image and click "Create"

![alt text](https://github.com/techtutorials/IoT-Google-Sheets-Data-Analysis-on-Jupyter-Notebook/blob/master/images/google3.png "Help Image 3")

6. Browser will automatically take you back to the next screen. Choose your project from the drop down at the top. And click on "Enable APIS and Services".

![alt text](https://github.com/techtutorials/IoT-Google-Sheets-Data-Analysis-on-Jupyter-Notebook/blob/master/images/google4.png "Help Image 4")

7. Search for "Google Sheets API" and click on it. Browser will take you to next screen.

![alt text](https://github.com/techtutorials/IoT-Google-Sheets-Data-Analysis-on-Jupyter-Notebook/blob/master/images/google5.png "Help Image 5")

8. Click on "Enable API"

![alt text](https://github.com/techtutorials/IoT-Google-Sheets-Data-Analysis-on-Jupyter-Notebook/blob/master/images/google6.png "Help Image 6")

9. Browser will take you back to the next screen. Click on "Credentials" from the left menu.

![alt text](https://github.com/techtutorials/IoT-Google-Sheets-Data-Analysis-on-Jupyter-Notebook/blob/master/images/google7.png "Help Image 7")

10. On the next screen, Click on "Create Credentials" from the top menu and then "Service Account".

![alt text](https://github.com/techtutorials/IoT-Google-Sheets-Data-Analysis-on-Jupyter-Notebook/blob/master/images/google8.png "Help Image 8")

11. Give a name to the "Service Account". Click "Create".

![alt text](https://github.com/techtutorials/IoT-Google-Sheets-Data-Analysis-on-Jupyter-Notebook/blob/master/images/google9.png "Help Image 9")

12. Click "Select a role" -> "Service accounts" -> "Service account user".

![alt text](https://github.com/techtutorials/IoT-Google-Sheets-Data-Analysis-on-Jupyter-Notebook/blob/master/images/google10.png "Help Image 10")

13. Click "Continue".

![alt text](https://github.com/techtutorials/IoT-Google-Sheets-Data-Analysis-on-Jupyter-Notebook/blob/master/images/google11.png "Help Image 11")

14. Click "Done".

![alt text](https://github.com/techtutorials/IoT-Google-Sheets-Data-Analysis-on-Jupyter-Notebook/blob/master/images/google12.png "Help Image 12")

15. Note down the "Email" value and then "Click" on the email value. We will use the email value later. Don't worry if you don't note it. you can always copy it later. 

![alt text](https://github.com/techtutorials/IoT-Google-Sheets-Data-Analysis-on-Jupyter-Notebook/blob/master/images/google13.png "Help Image 13")

16. Click "Add Key" -> "Create new key".

![alt text](https://github.com/techtutorials/IoT-Google-Sheets-Data-Analysis-on-Jupyter-Notebook/blob/master/images/google14.png "Help Image 14")

17. Create a json key for your Service Account.

![alt text](https://github.com/techtutorials/IoT-Google-Sheets-Data-Analysis-on-Jupyter-Notebook/blob/master/images/google15.png "Help Image 15")

18. A private key is downloaded to your computer. Upload it to your Jupyter Environment/ save it in the same folder where your notebook is. 

![alt text](https://github.com/techtutorials/IoT-Google-Sheets-Data-Analysis-on-Jupyter-Notebook/blob/master/images/google16.png "Help Image 16")

19. Click on Save at the bottom. Then click on "Back" button at the top.

![alt text](https://github.com/techtutorials/IoT-Google-Sheets-Data-Analysis-on-Jupyter-Notebook/blob/master/images/google17.png "Help Image 17")

20. Go to ![Google Drive](https://drive.google.com) and make a spreadsheet. Create 2 columns, "Temperature" and "Humidity". Fill your data.

21. Get your spread sheet id

![alt text](https://github.com/techtutorials/IoT-Google-Sheets-Data-Analysis-on-Jupyter-Notebook/blob/master/images/google18.png "Help Image 18")

22. Click on "File" -> "Share" and share it with your service account email

![alt text](https://github.com/techtutorials/IoT-Google-Sheets-Data-Analysis-on-Jupyter-Notebook/blob/master/images/google19.png "Help Image 19")

![alt text](https://github.com/techtutorials/IoT-Google-Sheets-Data-Analysis-on-Jupyter-Notebook/blob/master/images/google20.png "Help Image 20")

23. Make following changes in your code and execute your code.

![alt text](https://github.com/techtutorials/IoT-Google-Sheets-Data-Analysis-on-Jupyter-Notebook/blob/master/images/google21.png "Help Image 21")

===========================Enjoy===========================

#### As an optional steps, you can do following to update your Google Sheet data regularly using Raspberry Pi / ESP82266 and DHT 22 Sensor

