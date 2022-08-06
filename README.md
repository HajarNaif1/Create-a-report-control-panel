# Create a report control panel
###  database is  :mag_right: 
#### A database is information that is set up for easy access, management and updating. Computer databases typically store aggregations of data records or files that contain information, such as sales transactions, customer data, financials and product information.
### Start
```
php -S 127.0.0.1:8080
```
### GET request
```
curl http://localhost:8080/index.php/numbers/list\?limit\=20
```
### POST request
```
curl --location --request POST 'http://localhost:8080/index.php/numbers/post' \ --form 'number="150"'
```
