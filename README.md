# **"Movies Actors"**

### Description

Personal project done during my bootcamp where you can see actors name, photo and popularity. I used a file json as basic data base to have some default actors and start the project. The splash page comes with 5 actors but you can add more randonly pressing the button "Add random". You can also delete any actor you want and organize the list by name or popularity.


### Technologies

- Bootstrap
- Javascript
- React

### MVP (Minimum Viable Produc)

App, display actors photo, name and popularity. Add random ones, organize by popularity or name. UI create with Bootstrap.

### User Stories

- **actors card** - user can see the actor card with photo, name and popularity.
- **add random actor** - add random actor by clicking at the buttom.
- **organize by popularity** - organize the actors by their popularity.
- **organize by name** - organize the actors by their name.
- **delete actors** - delete actors clicking at the delete buttom.

### Client / Frontend

### React Router Routes (React App)
| Path                      | Component            | Permissions                 | Behavior                                                                         |
| ------------------------- | -------------------- | --------------------------- | ---------------------------------------------------------------------------------|
| `/`                       | SplashPage (unique)  | public `<Route>`            | Home page, view the default 5 actors, add random, short by popularity or name and delete any from the list |

### Components

- SplashPage (Home - Unique Page)

### Data Structure
```
├── public
│   ├── _index.html
├── src
│   ├── components
│   │   ├── Button.js
│   │   ├── ContactList.js
│   │   ├── Header.js
│   │   ├── Table.js
│   ├── app.css
│   ├── app.js
│   ├── contacts.json
│   ├── index.css
│   ├── index.js
├── gitignore
├── package-lock.json
├── package.json
└── README.md
```

### Git
* [GitHub] ( https://github.com/jpsm83/movies-actors )