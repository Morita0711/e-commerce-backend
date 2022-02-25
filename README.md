# AngularProject-Backend-
You might want to consider this type of application as actually TWO applications.

The first is the backend, the API. You can use your PHP framework to build an API that will allow you to have data persistency, validation (business logic), etc... and forget about the front end for now, you are only building an API for the backend data.

The second part of the app is the AngularJS frontend. This includes all of the views and everything that the client sees. None of that is coming from the backend.

This allows you to use the backend API (the PHP bit) to act as the data store, with it's own validation for safety, while having the seamless user experience and basic client side validation from AngularJS.
