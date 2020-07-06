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


<p align="center">
  <img src="https://github.com/nursnaaz/ML-Heroku-Deployement/blob/master/Screenshot%202020-07-07%20at%202.16.26%20AM.png" width="600" title="hover text">
 
</p>


8. After completing you can see a message app is deployed with an URL

9. Take the url and launch it in the browser

10. To check logs

```heroku logs --tail ```

Thats it

Reference:
https://github.com/PaacMaan/cars-price-predictor
