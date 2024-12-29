- Unit 37.1 - Intro to Node-pg
- pg
    - Allows us to establish a connection to a database and execute SQL
        - $ npm install pg
        - the file db.js contains the connection to the database using pg

____________________________________________________________________________
- Assignment - Biztime:
    - Install using npm i express pg
    - createdb biztime
    - psql biztime < data.sql

- Routes
    - GET /companies - Returns list of companies
    - GET /companies/[code] - return obj of company
    - POST /companies - adds a new company
    - PUT /companies/[code] - Edit existing company
    - DELETE /companies/[code] - Delete existing company
    - GET /invoices - Return list of invoices
    - GET /invoices/[id] - return obj of invoices
    - POST /invoices - Adds an invoice
    - PUT /invoices/[id] - Updates an invoice
    - DELETE /invoices/[id] - Deletes an invoice
    - GET /companies/[code] - Get company with specified code

- .env needs to have following info
    - PGUSER=user
    - PGPASSWORD=password
    - PGDATABASE=biztime

__________________________________________________________________
Be sure to download Node.js and install packages