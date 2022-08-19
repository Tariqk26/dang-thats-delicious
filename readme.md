## Sample Data

To load sample data, run the following command in your terminal:

```bash
npm run sample
```

If you have previously loaded in this data, you can wipe your database 100%
clean with:

```bash
npm run blowitallaway
```

That will populate 16 stores with 3 authors and 41 reviews. The logins for the
authors are as follows:

| Name          | Email (login)      | Password |
| ------------- | ------------------ | -------- |
| Wes Bos       | wes@example.com    | wes      |
| Debbie Downer | debbie@example.com | debbie   |
| Beau          | beau@example.com   | beau     |

## The Process

This Project was part of the Learn Node Course from Wes Bos, The Aim was to
create a node project using MongoDB to create a web site which reviews different
places to eat. This helped me understand the file structure and breakdown of
using a node backend, and using Controllers, models and routes to write
javascript. As well as learning Asyncronous JavaScript.

In the `index.js` file I built my own REST API which searches stores and is able
to create hearted stores.

## The Challenges

One of the challenges I found this course was handling user authentication, I
used `Passport.js` to handle the authentication in the app. Displaying the
Hearted Stores was difficult, I had an animation which ran when a store had the
class of `hearted__float` but it took me a while to figure out that the
animation wasn't triggering because there was a typo in the `heart` variable.

I also had issues getting paging to work, whichever page you would click on the
API would take you instantly to the last page, I realised this was due to a typo
in my `_pagination.pug` mixin pug file.

## Tools

- Node.js
- Mongo DB
- Passport.js
- Mongoose
- Pug
- Webpack
- Sass
- Express
- Heroku

## To Do
