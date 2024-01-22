# Bus Booking API

## API Endpoints

### User Signup
🔗 POST http://localhost:8080/api/auth/register

### User Login
🔗 POST http://localhost:8080/api/auth/login

### Search list of Buses from one city to another city
🔗 POST http://localhost:8080/api/bus/search

### Fetch Available seat of a bus
🔗 GET http://localhost:8080/api/bus/search/id

### Add the ticket to cart
🔗 POST http://localhost:8080/api/bus/cart/add

### Get all tickets available in cart
🔗 POST http://localhost:8080/api/bus/cart

### Book the ticket
🔗 POST http://localhost:8080/api/bus/book/id

### Delete ticket from cart
🔗 DELETE http://localhost:8080/api/bus/cart/${id}

### Get all booked tickets
🔗 POST http://localhost:8080/api/bus/book

### Cancel the booked ticket
🔗 DELETE http://localhost:8080/api/bus/book/${id}
