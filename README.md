# ![SimpleLoc](https://simpleloc.herokuapp.com/)

## Projet à retrouver sur Gitlab : https://gitlab.com/simpleloc

# Fonctionne de pair avec l'API, bien suivre les commandes du readme SVP

API : https://gitlab.com/simpleloc/api_simpleloc

## Preview https://simpleloc.herokuapp.com/

![](https://i.imgur.com/BkTYqJm.png)

---

## Installation Locale

### Installation API

`git clone git@github.com:luca-montaigut/api_simpleloc.git`

`cd api_simpleloc`

`bundle install`

`echo DEVISE_JWT_SECRET_KEY=\"$(rake secret)\" > .env`

(You have to add your Cloudinary API keys too)

`rails db:create && rails db:migrate`

`rails s`

Your API is now running on http://localhost:8080

### Installation FRONT

`git clone git@gitlab.com:simpleloc/front_simpleloc.git`

`cd front_simple`

`npm install`

`echo REACT_APP_API_URL='http://localhost:8080' > .env`

`npm start`

Your website is now running on http://localhost:3000

---

## Comptes tests

Tenant : tenant@yopmail.com

Renter : renter1@yopmail.com

Password pour les 2 : 123456


## 🐰 Auteurs

Luca Montaigut : https://github.com/luca-montaigut

Maxime Speroni : https://github.com/Laspargus

Nathan Chateau : https://github.com/nathan-ch

Hadrien Samouillan : https://github.com/DoubleLama

Nans Noel : https://github.com/nans64
