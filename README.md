
# Student Activity center (SAC) MNNIT Allahabad

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

---

**sacMnnit** is responsible for organising various cultural and technical events in MNNIT.

Here's our website:  [SAC18 | MNNIT](https://sacmnnit.herokuapp.com)

![Picture of the SAC](./SacMnnit/static/images/slider.jpg)

## Instructions

```
# Create a virtual environment
virtualenv --python=python3 sacenv

# Activate it
source sacenv/bin/activate

#Install all dependencies needed on the virtual environment
pip install -r requirements.txt

#Run the server
python manage.py runserver
```