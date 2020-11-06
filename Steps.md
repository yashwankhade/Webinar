# Steps to Deploy this repository on web

### Prerequitis
1. You should have git installed.
2. You should have python on your machine.
3. You should have IDE installed on your machine

### Steps:-
1. Fork the **Webinar** repository.
2. Now download Repository to local Machine.
3. Install Requirements.txt
4. Edit index.html(Templates/main/index.html) file as per your requirements.
5. Now use command *python manage.py runserver* or *python3 manage.py runserver*
6. If you see website running on local host Congrats you have created your website.
7. Now push the code to github


### Deployment
1. Now go to ***https://heroku.com/*** create your account.
2. create application with suitable name.
3. Now go to setting of app select buildpack as python.
4. Now go to deploy section select github and connect your forked repository.
5. Now click on deploy. If deployed successfully you will get url for app.
6. Add that url in allowed host of setting.py file on local machine and push again.
7. now deploy again. Hurray you have successfully deloyed your website.
