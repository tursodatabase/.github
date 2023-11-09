### What is Turso
  
Turso is a serverless SQL database on the SQLite dialect, built by the creators of [libSQL](https://turso.tech/libsql), the Open Contribution fork of SQLite.

Turso allows you to keep the benefits of SQLite, like developing locally on a file, but take it to production either by
* keeping multiple copies in sync,
* accessing it over HTTP with global replication at the Edge.

Replication is easy and affordable, and it is fully controllable through an API.

### Open Source

The Turso database is fully Open Source, and we [offer a managed service](https://turso.tech).
The main repository is [libSQL](https://github.com/tursodatabase/libsql), where you will find the SQLite-replacement library and the server code for HTTP access.
There are other repositories in this organization like the [turso CLI](https://github.com/tursodatabase/turso-cli).

### Code examples and experimental work

We keep code examples (including third-party contributed) and other experimental code that we haven't yet made the commitment to support in a separate organization.
Please find those at [turso-extended](https://github.com/turso-extended).
