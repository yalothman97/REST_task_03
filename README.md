1. Setup a virtual environment.
2. Fork the repository for [Django REST Task 3](https://github.com/JoinCODED/REST_task_03/) in JoinCODED’s Github and Clone it.
3. Install the packages from the requirements file.
4. Create a login api. [This](https://getblimp.github.io/django-rest-framework-jwt/) will help.
4. Create a Restaurant create API view:
    * It should use the same serializer as the update view.
    * The `flight` should get assigned automatically to the booking. The flight id should be retrieved from the url.
    * The `user` should get assigned automatically to the booking. The **logged in user** who is creating the booking should get assigned as the `user`.
    * Create a `URL` with this path `book/<int:flight_id>/` for this view and test it in `postman`.
    * Replace the api in the **frontends** `book` view with this api.
7. Push your code
