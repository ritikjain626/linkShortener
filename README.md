Step 1: docker run -p 3306:3306 --name db-mysql -e MYSQL_ROOT_PASSWORD=root -d mysql

Step 2: docker exec -it db-mysql bash

Step 3: mysql -u root -p

Step 5: Enter password 'root'

Step 6: ALTER USER root IDENTIFIED WITH mysql_native_password BY 'root';

Step 7: CREATE DATABASE shortener_dev;

Step 8: Go to folder Link Builder

Step 9: RUN node index.js

Step 10: Navigate to http://localhost:3000 in your browser to test it!