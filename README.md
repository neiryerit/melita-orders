# Melita-orders
Java Technical Assessment based on Installment Orders. It's focus on MS architecture, design patterns, containerization, messagin broker, security, testing and Java Spring suite

# Flowchart
![melita-orders-flow](https://github.com/user-attachments/assets/3e92c22e-03be-4d1c-a64a-c0e9b55bf57f)

# Architecture
![melita-orders-test-architecture](https://github.com/user-attachments/assets/e75d2f3a-7a09-4567-b6b2-61211f21b68e)

# Source code folders
![melita-orders-test-repo](https://github.com/user-attachments/assets/788cb5f3-3bff-4b26-a711-25e9cb77f702)

# Config files server repo
https://github.com/neiryerit/config-files

# docker Commands for run
(Run it from the project's folder, where Dockerfile is placed)

`docker build -t eureka .`

`docker build -t configserver .`

`docker build -t customers .`

`docker build -t products .`

`docker build -t orderQueue .`

`docker build -t orderpub .`

`docker build -t ordersub .`

`docker compose up -d --build`

# Postman collection
(apis availables from swagger as well http://{server}/swagger-ui/index.html)

[melita-orders.postman_collection.json](https://github.com/user-attachments/files/18668268/melita-orders.postman_collection.json)
