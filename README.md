
# 🍔 FoodFrenzy

**FoodFrenzy** is a dynamic and user-friendly online food ordering platform that brings the convenience of restaurant dining directly to your doorstep. It provides customers with a seamless experience to browse menus, place orders, and give real-time ratings. At the same time, it empowers restaurant owners to efficiently manage their menus and orders, ensuring smooth operations and timely food delivery.



## Key Features

- **User Authentication**: Secure login and registration for both users and admins.
- **Inventory Management**: Admins can add, update, and delete food items; track stock levels.
- **Order Management**: Users can browse, add items to cart, place orders, and track order status; admins can manage all orders.
- **Dynamic Pages with Thymeleaf**: Server-side rendering for fast and responsive UI.
- **Role-Based Access Control**: Separate dashboards and permissions for admins and users.




## 🛠️ Tech Stack

- **Backend**: Java, Spring Boot, Spring MVC
- **Frontend**: HTML, CSS, Thymeleaf
- **Database**: MySQL
- **Build Tool**: Maven







## Setup and Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-repository-url/FoodFrenzy.git
    ```

2. Navigate to the project directory:
    ```bash
    cd FoodFrenzy
    ```



3. Run the project:
    ```bash
    mvn spring-boot:run
    ```

4. Access the application:
    - Navigate to `http://localhost:8080` in your browser. 


## Project Structure

```bash
src/
├── main/
│   ├── java/
│   │   └── com.example.foodfrenzy/
│   │       ├── controller/      # Contains all controllers
│   │       ├── model/           # Contains entity classes
│   │       ├── repository/      # Repository interfaces for database interaction
│   │       └── service/         # Service layer with business logic
│   ├── resources/
│   │   ├── templates/           # Thymeleaf templates for views
│   │   ├── static/              # Static assets (CSS, JavaScript)
│   │   └── application.properties  # Project configuration
│   └── webapp/
│       └── WEB-INF/
│           └── views/           # Additional view files
└── test/                        # Test cases for unit testing

