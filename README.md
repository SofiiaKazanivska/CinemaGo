# __CINEMA - APP 🍿👀🎞__

<sub>   
	
	"Cinema is a matter of what's in the frame and what's out.
	Martin Scorsese
	
 </sub>
 
 ![Movie Watching](https://media.giphy.com/media/ZcnTGzZtdOg5i/giphy.gif)

The application is built on Hibernate and Spring frameworks, using REST, SOLID, DRY principles, Three-Tier architecture:

- Controllers - user interaction with the program: sending requests and receiving responses;
- Services - business logic;
- Data access object (DAO) - interaction of the program with the database.


### STRUCTURE
>
>- config - app's configuration
>
>- dao - Data Access Object interfaces and their implementations
>
>- dto - Data Transfer Object
> 
>- exception - custom DataProcessingException
>
>- lib - email and password validators with custom annotations
>
>- model - models that represent entities in the database
>
>- service - services and their implementations that embody business logic
>
>- util - contains a DateTime pattern
>
>- resources - files with database configuration
>
>- controller - controllers for endpoints:

- `POST /login` - authentication
- `GET /logout` - logout


__AuthenticationController:__

- `/register` - new user registration

__CinemaHallController:__

- `/cinema-halls/` - show all cinema-halls
- `POST /cinema-halls/` - add a new cinema hall (only ADMIN role)

__MovieController:__

- `GET /movies/` - show all movies
- `POST /movies/` - add a new movie (only ADMIN role)

__MovieSessionController:__

- `GET /movie-sessions/available/` - show all available movie sessions
- `POST /movie-sessions/` - add a new movie session (only ADMIN role)
- `PUT /movie-sessions/${id}/` - update a movie session by id (only ADMIN role)
- `DELETE /movie-sessions/${id}` - update/delete a movie session by id (only ADMIN role)

__OrderController:__

- `GET /orders/` - show user's order history
- `POST /orders/complete` - complete order

__ShoppingCartController:__

- `GET /shopping-carts/by-user/` - show all tickets added to user's shopping cart
- `PUT /shopping-carts/movie-sessions/` - update shopping cart by movie session id

__UserController:__

- `GET /users/by-email/` - show user's information by email (only ADMIN role)







### 📩 Contact
[Kazanivska Sofiia](https://www.linkedin.com/in/sofiia-kazanivska-40a413232/) <br>
sofiakazzz@gmail.com



