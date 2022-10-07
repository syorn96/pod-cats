# Pod Cats

## Project Idea and Descriptions

Pod Cats is a social media and educational application designed for your pet cat. This online application will allow cat owners to post and share pictures of their cute and diabolical best friend. Additionally users will be able to learn random cat facts and read random cat articles.

## Choice of API and proof of concept

## ERDs


## Restful Routing Chart
#### Users

| Method | URL pattern | Action | Description |
|:------:|:-----------:|:------:|:-----------:|
| POST   | /users | Create | Create new user |
| GET    | /users/login | Read | Render form for users to log in |
| POST   | /users/login | Read | Verify user login info |
| GET    | /users/logout | Read | Log out user & user cookie id |
| GET    | /users/new | Read | Render form for creating new User |
| GET    | /users/profile | Read | Display User information & FREE horoscope |
| GET    | /users/profile/account | Read | Render form for updating user information |
| PUT    | /users/profile/account | Update | Edit/update User information |
| DELETE | /users/profile/account | Delete | Delete User from DB |

#### Cat
| Method | URL pattern | Action | Description |
|:------:|:------:|:------:|:-----------:|
| GET    | /users/:id/meditate | Read | Show 50 random quotes |
| POST   | /users/:id/meditate | Create | Add quote(s) to user's reflect page |

## Wireframes



## Userstories
* As a user I want to be able to create an account
* As a user I want to be able to create a new Cat post (image, caption, header)
* As a user I want to be able to remove a cat post from my profile
* As a user I want to learn more about cat breeds
* As a user I want to see a LOT of cat pictures
* As a user I want to be able to edit my existing account details (display name)

## MVP Goals
* Personal Cat App
* Create an account
* Be able to post pictures of your Cat
* Allow users to comment on posts
* Functioning Routes


## Stretch Goals
* Allow users to share posts with other users in a feed ???
* Available Cat adoption?
* Cat articles, facts (third API)
* Allow users to comment on posts
* Edit favicon
* Limited feed of posts, unless users scroll to display additional posts 
