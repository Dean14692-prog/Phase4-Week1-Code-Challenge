
# Superheroes API - Phase 4 Code Challenge

## Description
This is a Flask-based RESTful API developed as part of the Software Engineering curriculum at Moringa School. It manages **Superheroes**, their **Powers**, and the relationships between them. The API supports full CRUD functionality and follows proper REST conventions.


## Technologies
- Python 3.x  
- Flask  
- Flask-SQLAlchemy  
- Flask-Migrate  
- SQLite3 (for development)



## Project Structure

```bash
superheroes-api/
├── app.py
├── config.py
├── models.py
├── migrations/
├── seed.py
├── requirements.txt
├── challenge-2-superheroes.postman_collection.json
└── README.md
```
##  Setup Instructions
- Clone the repo

~~~bash
git clone git@github.com:Dean14692-prog/Phase4-Week1-Code-Challenge.git
cd superheroes-api

~~~

- Create Virtual Environment
```bash
pipenv install && pipenv shell
```




- Set up the database
``` bash
flask db init
flask db migrate -m "Initial migration"
flask db upgrade
```
- Seed the database
``` bash
python seed.py
``` 
- Run the server
``` bash
- flask run
```
## Postman Collection
- Use the provided Postman collection to test your API:

How to Import:
- Open Postman.

- Click Import > Upload Files.

- Select the file challenge-2-superheroes.postman_collection.json.

- Use the predefined requests to test your endpoints.

## Features
- CRUD routes for Heroes and Powers.

- Input validation and proper error handling.

## Future Improvements
- Add authentication and user accounts.

- Implement pagination for large lists.

- Deploy with Render.

## Contact
- For support or questions, reach me at:

- Email: dennis.ngui@moringaschool.com

- GitHub:  
~~~bash
@Dean14692-prog
~~~
