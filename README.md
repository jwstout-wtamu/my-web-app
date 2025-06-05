# README
# Readme - test with pipeline
---
## This repo will be for the final project
#### This readme is for markup only at this time.
# Project Tech Specs
The guidance on prototype development creates a Baseline, Good, Better, Best approach for Django feature targeting that will provide the best chance for you to realize a rich prototype.

### Assignment Requirements:
- [x] For this assignment, create a new Github repository that will be used for your final project Django prototype.  https://github.com/jwstout-wtamu/6325-SATXFSHD-Project.git
- [x] This repository should be for the final project only. 
### This web application will be a Community of knowledge blog regarding the FSHD Community at the local level.
| Site major features      | Description |
| ----------- | ----------- |
| Local commuity blog      | You can sign up for the to post stories and blogs in the this local commuity       |
| Links to resources   | Resourse links to the FSHD Society        |
| Local events   | Local calendar events        |
| FSHD merchandise   | Where to purchase merchandise        |
| Amazon Smile donations  | What is Amazon Smile and how it's used for donations        |
| Local commuity news letter   | 

#### [Link to  separate table that itemizes which Django features I'll be using](https://github.com/jwstout-wtamu/6325-SATXFSHD-Project/blob/main/django_feature.md)

- [x] What domain name you are planning to use: 	
	- [x] satx-fshd.org will be the domain name I'll be using (Letsencrypt does not like private domains...like .social)

#### I will be exploring both options. Heroku seems to be the easy win, but I wold like to see if can get it running on a VPS as well (digitalocean)
	- [ ] Heroku
	- [ ] VPS
### Update
I've used the open code below with fit with how I wanted the site to look. These are items the book does not cover very well.
I've changes the layout and option to better suite what I want to deliver.
I've also integrated some Java in the build as well.
MIT LIC file is also in the repo. 

### Update 11/10/2022
### Completed:
Can open password forms fine 
### Update 11/16/2022
Allowe to change password form updated

### Update 11/21/2022
### Issues
Sendgrid emails is now working 



<!--
This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to c<!--
*** Thanks for checking out this README Template. If you have a suggestion that would
*** make this better, please fork the repo and create a pull request or simply open
*** an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url] 
[![Forks][forks-shield]][forks-url] 
[![Stargazers][stars-shield]][stars-url] 
[![Issues][issues-shield]][issues-url] 
![Hireable](https://cdn.rawgit.com/hiendv/hireable/master/styles/default/yes.svg) 

# Django Blog

>  A Blog built with Django where bloggers can signup/login, and perform CRUD operations for posts. Bloggers can search per tags or headlines and comment in posts.


## Built With

- DJANGO
- BOOTSTRAP
- CKEDITOR
- PILLOW
- DJANGO FILTERS
- GITHUB ACTIONS
- VSCODE

## Getting Started
### Usage
To have this app on your pc, you need to:
* [download](https://github.com/javitocor/Blog-Django/archive/main.zip) or clone this repo:
  - Clone with SSH:
  ```
    git@github.com:javitocor/Blog-Django.git
  ```
  - Clone with HTTPS
  ```
    https://github.com/javitocor/Blog-Django.git
  ```

* In the project directory, you can run:

Create virtual enviroment with:

``` bash
py -m venv project-name
project-name\Scripts\activate.bat
```
Install dependencies in your home folder with:

``` bash
   pip install -r requirements.txt
```

Run migrations:

``` bash
   py manage.py makemigrations
   py manage.py migrate
```
Run server:

``` bash
   py manage.py runserver
```
Access the page by typing in your web browser

``` bash
   http://127.0.0.1:8000/
```

## Author

👤 Javier Oriol Correas Sanchez Cuesta 
- Github: [@javitocor](https://github.com/javitocor) 
- Twitter: [@JavierCorreas4](https://twitter.com/JavierCorreas4) 
- Linkedin: [Javier Oriol Correas Sanchez Cuesta](https://www.linkedin.com/in/javier-correas-sanchez-cuesta-15289482/) 

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](https://github.com/javitocor/Blog-Django/issues).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments 🚀

- [Django Docs](https://docs.djangoproject.com/en/3.2/)
- [CKeditors](https://django-ckeditor.readthedocs.io/)
- [Django-Filters](https://django-filter.readthedocs.io/)
## 📝 License

This project is [MIT](https://github.com/jwstout-wtamu/6325-SATXFSHD-Project/blob/main/LICENSE) licensed.

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/javitocor/Blog-Django.svg?style=flat-square
[contributors-url]: https://github.com/javitocor/Blog-Django/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/javitocor/Blog-Django.svg?style=flat-square
[forks-url]: https://github.com/javitocor/Blog-Django/network/members
[stars-shield]: https://img.shields.io/github/stars/javitocor/Blog-Django.svg?style=flat-square
[stars-url]: https://github.com/javitocor/Blog-Django/stargazers
[issues-shield]: https://img.shields.io/github/issues/javitocor/Blog-Django.svg?style=flat-square
[issues-url]: https://github.com/javitocor/Blog-Django/issuesover:
