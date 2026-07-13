Site premium pentru Restaurant Masa Boierului.

Preview local cu backend:

npm install
npm start

Pe Railway:
- adauga un serviciu PostgreSQL in acelasi proiect
- leaga variabila DATABASE_URL la aplicatie
- optional seteaza ADMIN_USERNAME si ADMIN_PASSWORD
- Railway va rula npm start

Serverul creeaza automat tabelele pentru rezervari, comenzi si clienti.
Fara DATABASE_URL, aplicatia porneste local cu stocare temporara in memorie.
