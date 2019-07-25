# prisma-vagrant-demo
A repo which provides Vagrant support to stand up an instance of Postgres, Prisma, Typescript and PGAdmin

1. Clone the repo
2. Edit the .env file to provide your desired credentials
3. Assuming you have Vagrant already installed, 'vagrant up' to start
4. Prisma is available at http://localhost:9901/_admin
5. PGAdmin is available at http://localhost:9903
6. Postgres is available on port 9902
7. Once vagrant up is done, prisma deploy

If you want to connect to the database from PGAdmin, create a new server connection.  On the General tab, provide a name.  On the Connection tab, specify a host name.  Use the username and password and database used in the .env file.

Helpful links:
https://www.prisma.io/docs/get-started/01-setting-up-prisma-existing-database-TYPESCRIPT-t003/






