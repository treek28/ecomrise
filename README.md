🛒 E-Commerce Web Application
Mini Project – Web Technology & Internet
Faculty of Information Technology
📘 Project Overview
This project is a simplified e-commerce application developed using Spring Boot and Thymeleaf as part of the Mini Project requirement for the Web Technology & Internet course. The system supports basic e-commerce functionality and distinguishes between two user roles:

- Customer – browse and order products.
- Admin – manage product listings and oversee orders.
🧩 User Roles & Features
👤 Customer
- View and explore a list of products.
- Check product details.
- Add products to a shopping cart.
- Manage the cart and proceed to checkout.
- Register and log in to track orders.
👨‍💼 Admin
- Add, update, and delete products and category.
- View incoming orders and change their status.
🛠️ Tech Stack
- Backend: Spring Boot, Spring Data JPA, Spring Security
- Frontend: Thymeleaf, Spring MVC
- Styling: Bootstrap
- Database: PostgreSQL
- Build Tool: Maven
✨ Core Features
Backend (Spring Boot)
- Role-based access (USER and ADMIN) using Spring Security
- CRUD operations for Product entity
- Order APIs and entity relationship management
- RESTful API design with proper HTTP verbs
- Backend validation using Spring’s validation framework
Frontend (Thymeleaf)
- Dynamic pages for product listing, cart, and order flow
- Bootstrap for responsive styling
- Integration with backend APIs
- Login and registration forms
- JavaScript for cart operations and UI interactivity
📋 Additional Requirements
- Proper error messages and validation for forms
- Deployment on Heroku or other platforms
- Publicly hosted GitHub repository
- Submission link shared via Google Classroom
📦 Prerequisites
- Java 21
- Maven
- PostgreSQL (or MySQL)
- Git
- IDE (IntelliJ IDEA or Eclipse)
⚙️ Setup Instructions
1. Create a Spring Boot Project with dependencies:
   - Spring Web, Spring Data JPA, Spring Security, Thymeleaf, PostgreSQL Driver

2. Configure database in `application.properties`:
   spring.datasource.url=jdbc:postgresql://localhost:5432/Ecommerce1
   spring.datasource.username=your_username
   spring.datasource.password=your_password

3. Define Entities: Product, User, Order
4. Create corresponding JPA Repositories
5. Implement Security Configurations
6. Develop REST APIs and Thymeleaf templates
🚀 Running the Project Locally
1. Clone the repository:
   git clone https://github.com/your-username/ecommerce-web-app.git

2. Navigate to the project folder:
   cd ecommerce-web-app

3. Update `application.properties` with your DB credentials
4. Build the project using:
   mvn clean install

5. Run the application:
   mvn spring-boot:run

6. Open browser at: http://localhost:8080
☁️ Deployment
- Use Heroku CLI for deployment
- Add a Procfile with: web: java -jar target/app-name.jar
- Configure database variables in Heroku dashboard
- Push project to Heroku
❗ Error Handling
- Backend: Custom exception handling using @ControllerAdvice
- Frontend: User-friendly messages with Thymeleaf templates
- Validation: Server-side validation and error reporting
🤝 Contributing
1. Fork the repository
2. Create a new branch: git checkout -b feature-name
3. Make changes and commit
4. Push to your fork and open a pull request
📄 License
This project is licensed under the MIT License.
📤 Submission
Source code and documentation are hosted on GitHub. The link has been shared via Google Classroom.
