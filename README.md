# Covid-Bed-Slot-Management
### DBMS Project on covid bed slot bookiing
### Install VS CODE
### Install required Libraries like code runner, live server, python, js and etc
### Run main.py
### Ctrl + click on the link
### Check Requirements.txt for more info



### Configuration
Secrets are read from environment variables, not from files in the repo. See `.env.example`:
- `SECRET_KEY`: Flask session key (a random one is generated per run if unset)
- `DATABASE_URL`: defaults to `mysql://root:@localhost/covid`
- `ADMIN_USERNAME` / `ADMIN_PASSWORD`: admin login is disabled until both are set
- `FLASK_DEBUG=1`: enables debug mode for local development only

Hospital user passwords are stored as Werkzeug password hashes.
