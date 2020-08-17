Getting started with MemSQL Stored Proceures and C#
===================================================


Whether you're using an ORM like Entity Framework or straight SQL, you can get started with MemSQL fast. Here's an introductory sample of using MemSQL stored procedures with C#. This sample includes all the CRUD methods: Create, Read by id, Read all, Update, and Delete.

Usage
-----

1. [Sign up](https://msql.co/2E8aBa2) for a free MemSQL license. This allows you to run 4 nodes up to 32 gigs each for free.

2. Spin up MemSQL either through a [Helios trial](https://msql.co/3iQ0SE8), Containers, or by [installing MemSQL](https://msql.co/3ay2PCb) on a supported Linux distribution. This sample includes a `docker-compose.yaml` that will spin up the database and run `init.sql`, so you need only grab your license key from the [MemSQL portal](https://msql.co/3fZoxjO) and then `docker-compose up`.

3. Adjust the connection details in `Program.cs`, `dotnet restore`, and run it.


License
-------

MIT
