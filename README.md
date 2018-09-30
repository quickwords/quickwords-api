# README

### Steps to set up project
* Ruby version 2.5.1p57 

* clone repo
   ```
   git clone https://github.com/quickwords/quickwords-api.git
   cd quickwords-api
   ```


* install dependecies
    ```
    bundle
    ```
* import **master.key** and **.env.local** to the root directory of the project

* create database user
  ```
  psql
  CREATE USER quickwords WITH CREATEDB PASSWORD '<<our_password>>';
  
  ```
  

* Database initialization
  ```
  rails db:setup
  ```

    ***For missing credentails and files ask @gtluszcz**