## Release 0: Initial Project
- project init
    - add vue router
    - add pinia
- init vue
- remove boiler plate composition api, pinia, router
- change initialization to options api
- change App.vue to
```html
<h1>hello world</h1>
```


## Release 1: Create Vue Initial Template
- add bootstrap to index.js
- remove import css in main.js
- move from index.html as vue component
- instantiate router
- instantiate store
- add router to pinia as plugin

## Release 2: Router
- navigate as page move on
    - /login
    - /animes
    - /animes/add

## Release 3: Auth
- add login to store and navigate to /animes
- add navigation guard
- add logout

## Release 4: Fetch
- fetch animes and attach to dom
- fetch anime by id and attach to dom

## Release 5: Mutable
- add form to create anime
- remove anime by id