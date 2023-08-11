## Final Project for CS 257: Software Design
### Carleton College, Spring 2022
This is a database-backed website that can search products carried in US grocery stores. Users can conduct searches based on criteria such as brand and ingredient, or simply by the product's name. For detailed guidance, refer to the 'usage.txt' file.

### How to run the flask app:
*  connect to perlman and clone the team repo
*  go to ../Backend
*  create psqlConfig.py with a database name (teamc). a user name (teamc), and a password
*  run: psql -U teamc -h localhost -d teamc < createtable.sql
*  run: psql -U teamc -h localhost -d teamc
*  run: \copy productTable FROM 'UpdatedFinalData.csv' DELIMITER ',' CSV
*  go to ../Code
*  run: python3 flaskapp.py

### Team members: 
* Isabella Cha
* Kana Hashimoto


