# ML-Heroku-Deployement


1. Siguu and create a heroku account

```https://signup.heroku.com/```

2. Install Heroku CLI

```https://devcenter.heroku.com/articles/heroku-cli```

3. Clone the code to the local and check if it is working

```git clone https://github.com/nursnaaz/ML-Heroku-Deployement.git```

4. Run it in local using the command after traversing into the folder


``` pip install -r requirements.txt```


```python app.py```

or 

``` gunicorn app:app -b 0.0.0.0:8080```

5. Login to your Heroku account 


```heroku login```

6. Create a heroku app

```heroku create <NAME OF THE APP YOU WANT IT TO GIVE>```

7. Push the code, build and deploy using Heroku

```git push heroku master```

8. After completing you can see a message app is deployed with an URL

9. Take the url and launch it in the browser

Thats it


