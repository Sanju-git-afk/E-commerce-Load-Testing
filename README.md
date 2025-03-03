Project Overview:
This project performs load testing on AutomationExercise using Apache JMeter. It simulates multiple users performing various e-commerce actions, such as:
  Homepage Load Test
  Product Search
  Add to Cart
  Checkout & Payment
This helps in identifying performance bottlenecks and ensuring scalability under high traffic.

Tools & Technologies Used
   Apache JMeter - Performance Testing
   GitHub - Version Control
   Jenkins - CI/CD Integration
   Ubuntu/Linux Terminal - Command-line execution

Test Scenarios & Configurations
    Homepage Load Test
         Simulates 50 users loading the homepage (/).
         Checks response time & error rate.
    Product Search
         Simulates users searching for T-shirts (/products?search=T-shirt).
         Measures response time for product search queries.
     Add to Cart
        Simulates adding a product to the cart (/add_to_cart).
        Validates response under high user load.
    Checkout & Payment
        Simulates checkout & payment process (/checkout).
        Ensures transaction success rates.



   Test Results & Analysis
        Response Time: Checks how fast the website responds.
        Throughput: Ensures the website can handle multiple users.
        Error Rate: Identifies failed transactions.
