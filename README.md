# Simple_Ecommerce_Application

A simple Ecommerce Application where users can browse electronic products, add them to a cart — all with full front-end and back-end integration.

# Project Tasks Covered

-  Create the front-end layout using **HTML**, **CSS**, and **JavaScript**
-  Implement a back-end using **Java** to handle product data and cart management
-  Connect the front-end and back-end using **API calls (via `fetch()` in JS)**

# Features

- Product categories: Mobiles, Laptops, PCs, Bluetooth, Headphones
- Add to cart
- Search products
- Remove items from the cart
- Backend integration with MySQL

# Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Java Servlets, JDBC, Gson 
- **Database**: MySQL (via JDBC)
- **Server**: Jetty

# Required JAR Files

Make sure these JARs are added to your `lib/` folder or project dependencies:

- `mysql-connector-j-9.1.0.jar` (MySQL JDBC driver)
- `gson-2.10.1.jar` (For JSON handling)
- `javax.servlet-api-4.0.1.jar`
- Jetty Server JARs (if you're using Jetty instead of Tomcat):
     - `jetty-server-9.4.53.v20231009.jar`
     - `jetty-servlet-9.4.53.v20231009.jar`
     - `jetty-util-9.4.53.v20231009.jar`
     - `jetty-http-9.4.53.v20231009.jar`
     - `jetty-io-9.4.53.v20231009.jar`
     - `jetty-security-9.4.53.v20231009.jar`
     - `jetty-webapp-11.0.6.jar`

# Setup Instructions

1. **Clone the repo** or copy the files to your local project.
2. **Create the Database**:
   - Import sql file into MySQL.
3. **Configure DB Connection**:
   - Set your DB URL, username, and password in DBConnection.java
4. **Add all JARs** to your project classpath.
5. **Deploy the app** using Jetty or Tomcat.
6. Open `http://localhost:8080/index.html` in your browser.

# Output Screens


![Screenshot 2025-04-12 145338](https://github.com/user-attachments/assets/e63df30b-e256-4887-a9e2-4d0530f57c21)


![Screenshot 2025-04-12 145414](https://github.com/user-attachments/assets/2f10abc7-9e59-4e52-9405-cf233b03a4fe)


![Screenshot 2025-04-12 145430](https://github.com/user-attachments/assets/1cd1e4ea-3161-44b4-8668-5c33c188c250)


![Screenshot 2025-04-12 145448](https://github.com/user-attachments/assets/02ade3df-fda9-4db4-9dfb-89f96e30af6e)


![Screenshot 2025-04-12 145457](https://github.com/user-attachments/assets/ad416efe-0bb5-4eb4-9ee3-40a39727ac6b)




