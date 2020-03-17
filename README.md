# personal_website
Personal website of Ryan Bradon (Me).
---
This web-app is powered with the following tech-stack:

    - Python (Language). 
    - Django (Model/Template/View Framework)
    - Wagtail.io (A better Django)
    - Gunicorn. Async worker (reverse proxy)
    - Nginx (Serves HTTP)
    

### But why?  
Friends don't let friends develop sites on Word Press.
Using Python and Django, I feel this comes out as #1 for security, robustness, extensibility and modular use of code, while being developer friendly. 


### Installation
**Get Source**:  
`git clone https://github.com/ryan-bradon/personal_website`

**Install Virtual Environment**  
`python3 -m pip install pipenv`  
`pipenv shell --python 3.7`  


**Install Wagtail**  
`pip install wagtail`
`wagtail start mysite`
`cd mysite`
`pip install -r requirements.txt`  


**Configure your new wagtail site**
`pip install -r requirements.txt `

### TODO:
TODO: Finish env setup.
TODO: Demo/Document DB configuration.
TODO: Demo/Document deployment to Azure, AWS, Google Cloud, Heroku.
