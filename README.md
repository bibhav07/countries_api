# countries_api
This project is an example of Django Rest Framework, which is used for building and api (application programming interface). 
In this project I have created 2 simple api, project is only focused on building an api with Django Rest Framework.
1) First api proviedes the data about currency of a particular contury
2) second api provides the data about capital of a particular country

You can check the final project that i have hosted on https://bibhav-json-api.herokuapp.com/

Below is the example to pull data in python language.

  import requests

  url = "https://bibhav-json-api.herokuapp.com/country-capital/"

  payload={}
  headers = {}

  response = requests.request("GET", url, headers=headers, data=payload)

  print(response.text)
