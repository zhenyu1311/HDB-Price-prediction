You can use this web app to predict HDB prices. Data is updated as of 2021. This is previously hosted on Heroku but heroku no longer offer free hosting services. So you have to run the app locally by running the manage.py file. You may need to have django installed.

The data is not mine. Sourced from singstat.gov

Note: 


       1. Ensure you follow the entry format of the app. For example, the floor format is XX to XX, you have to input '04 to 06' , it will bug out if you enter , say '4 to 06' or '4 to 6'. 

      2. It is case sensitive. For example , you should input Redhill , but reDHilL will not work. 
      
      3. Only data that exist in the data files can be predicted, no extrapolation prediction are available. for example , highest floor in data is 45, but if you predict a the pricing for a house with 60 floor, the app will bug out.
