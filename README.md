# Description
headlights is a node based database versioning tool. The tool helps in maintaining data base versions by keeping data base changes in form of json files.

headlights need basic configuration to connect with the application database and populate the database changes according to the data provided.

# Use Case
For code-first approach, the code is used to populate the database. While using database-first development approach, database is to be populated using scripts. Even for local development server, database versions to be maintained as per the development work. Here headlights can help in maintaining different versions of the database. Even when application team wants to migrate from one database to another, headlights can help in populating the database irrepective of underlying database software. The database changes can be progressively applied in each environment and if required rollback can also be done.

# Install & Usage
headlights is a CLI tool that could be installed via npm as below:
```bash
  npm install -g headlights
```