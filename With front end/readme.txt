*Diabetes prediction model is implemented using python and django 
*Prediction of diabetes based on input values is implemented by using the dataset to test and train the model
   1. Download the csv file ('diabetes.csv')
   2. Download the project folder (folder named as 'diabetes')
   3. Open pycharm and select open project 
   4. Select 'diabetes' folder from the download section
   5. Once the project is loaded, establish a django connection
   6. Check whether all the required packages are installed (open views.py file and check the imports)
   7.  Copy the path of diabetes.csv file from your downloads and paste it in the command which reads csv file
       [ copy path and paste in views.py : data = pd.read_csv(r'path') in python file ]
       (Note : views.py contains all the python code i.e Diabetes prediction model using LR method)
   8. Now type 'python manage.py runserver' in terminal
   9. You will get a server link in terminal, click on it
   10. A new web page appears in the default browser
   11. Home page will be visible click on 'Get started' button to view prediction web page
   12. Prediction web page appears, it has input boxes to fill in the input values to check whether the patient is diabetic or not
   13. Results are displayed appropriately in the webpage