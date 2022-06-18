# mydjango project
created a new virtual environment
cretaed new application using the django startapp command named blog
i added rthe blog to the main_project installed_apps
I created a model in the blog called Post and it has the following fields:
Title:A string of maxlength 200,used Djangos models.Charfield
Tex:Any amount of text using Djangos TextField
Author:A Foreign Key to the current user model using Djangos get_user_model function
Created_date:A date-time column using Djangos models.DateTimeField
Published_date:A date-time column using Djangos models.DateTimeField 
