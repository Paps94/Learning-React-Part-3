# Learning-React-Part-3
Creating a basic food ordering app to practice what I learned in Learning-React-Part-1 & 2

## Setup..

After cloning the repository and directing yourself to it all you need to do is!

```sh
npm install
```

```sh
npm run start
```

Additionally you will need to create a firebase project and in said project you need to create your dummy database

```sh
https://firebase.google.com/
```

After creating the project you can create a table and call it whatever you want, create the records in the form that Firebase accepts 

```sh
> m1
  -> name: '...'
  -> description: '...'
  -> price: '...'
> m2
  -> name: '...'
  -> description: '...'
  -> price: '...'
```

and replace your custom Firebase URL on line 32 in Cart.js

```sh
    await fetch('YOUR-FIREBASE-LINK/orders.json', {
```

and on line 15 in AvailableMeals.js (keep in mind that if you name the Firebase table something else you ened to replace the name after your custom link!)

```sh
        'YOUR-FIREBASE-LINK/meals.json'
```
