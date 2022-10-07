# Pod Cats

## Project Idea and Descriptions

Pod Cats is a social media and educational application designed for your pet cat. This online application will allow cat owners to post and share pictures of their cute and diabolical best friend. Additionally users will be able to learn random cat facts and read random cat articles.

## Choice of API and proof of concept

https://api.thecatapi.com/v1/images/search?limit=10

![cat api proof](./public/api.thecatapi.png)

## ERDs
![Entity Relational Diagrams](./public/project-3-erd.png)

## Restful Routing Chart

#### Users

| Method | URL pattern | Action | Description |
|:------:|:-----------:|:------:|:-----------:|
| POST   | /signup | Create | Create new user |
| GET    | /login | Read | Render form for users to log in |
| POST   | /login | Read | Verify user login info |
| GET    | /logout | Read | Log out user and user cookie id |
| GET    | /signup | Read | Render form for creating new User |
| GET    | /profile | Read | Display user info and cat posts |
| GET    | /profile/account | Read | Render form for updating user information |
| PUT    | /profile/account | Update | Edit/update user information |
| DELETE | /profile/account | Delete | Delete user from DB |

#### Cat
| Method | URL pattern | Action | Description |
|:------:|:------:|:------:|:-----------:|
| GET    | /cats | READ | Display feed of all (recent) cat posts |
| GET    | /cats/id/:id | READ | Display specific cat post |
| POST    | /cats/id/:id | CREATE | Create a new cat post |



## Wireframes
![Components](./public/wireframe-components.png)


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
