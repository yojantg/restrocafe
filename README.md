# Restro Cafe App in React & Redux + Django

```
This is an online food menu service for Restro Cafe. When you visit the restaurant, you often use the QR code to load the PDF of the menu. It has no image and is not easy to select. So we created the menu app where you can see food images with the needed information and select your items easily. During such an unprecedented time and social distancing, online menu card technology is a boon!

```
![image](https://user-images.githubusercontent.com/96680710/175112683-10f802ab-c1e6-445c-8f13-4a37cd67abe4.png)


## Live Demo

**This App uses a Heroku free plan, so I am afraid that it takes time to load the pages.**

Check out [FRONTEND LIVE DEMO](https://restrocafefrontend.herokuapp.com/) here!!

Check out [API LIVE DEMO](https://restrocafebackend.herokuapp.com/) here!!

## Tech used

```
* Frontend : React & Redux
* Backend : Django
```

## How to Install

1. Git Clone

```
git clone https://github.com/yojantg/restrocafe.git
```

2. Backend setting

```
cd backend
Python -m venv env
(For Mac) source env/bin/activate
(For Windows) env/Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
# Open http://127.0.0.1:8000/posts/
```


3. Frontend setting


```
cd frontend
npm install
npm start
# Open http://127.0.0.1:3000/
```
