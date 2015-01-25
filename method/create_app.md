# Creating an API

In this short book we are going to build ourselves an API that will help us manage our database of Cats.

We are going to create a database driven Rails API that outputs all of our Cat's details in JSON format. So, when someone wants to get our list of cats, they can call our API and get back a response like:

```json
{
    "cat": {
        "id": 1,
        "name": "Mr Tibbles",
        "bio": true,
        "owner": "Andrew",
        "picture": "http://..."
    }
}
```

And theoretically turn that into a lovely website.

> This book won't focus much on doing just that. We'll end by doing something very minimally with our API but this book shows you how to quickly prototype up an API that you can edit through an Admin panel.

In this book we will cover:

* setting up MySQL
* creating models with Rails
* serving JSON instead of HTML
* Installing an auto admin panel to manage your API's content
* API versioning

