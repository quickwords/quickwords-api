# 🚧🚧🚧 Work in progress 🚧🚧🚧
This is not a complete project nor should it be taken seriously, yet. Please do not create any issues not pull requests.

### Steps to set up project
* Ruby version 2.5.1p57 

* Clone the repo
```bash
git clone https://github.com/quickwords/quickwords-api.git
cd quickwords-api
```

* Install dependecies
```bash
bundle
```

* Import **master.key** and **.env.local** to the root directory of the project

* Create a database user
```bash
psql
CREATE USER quickwords WITH CREATEDB PASSWORD '<<our_password>>';
```  

* Database initialization
```
rails db:setup
```

**For missing credentails and files ask @gtluszcz**
