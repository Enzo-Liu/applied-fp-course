# Level 05

We need a place to store our Comments/Topics, so we're going to add a database
to our application, specifically the SQLite database. We've chosen SQLite
because it was the simplest to have up and running for the purposes of the
course.

There is an example module included for using PostgreSQL, however the course
will focus on the SQLite implementation.

For reference, the packages we will use to talk to our database are:

- [sqlite-simple](https://hackage.haskell.org/package/sqlite-simple)
- [sqlite-simple-errors](https://hackage.haskell.org/package/sqlite-simple-errors)

You will also need the [SQLite](https://www.sqlite.org/) database application
installed and available on your system.

Also we will not necessarily provide all of the required imports any more, there
may be other things you have to bring into scope.

Start in ``src/FirstApp/DB/Types.hs``, before moving to ``src/FirstApp/DB.hs``.

NB: The PostgreSQL example module is in ``src/FirstApp/DB/PostgreSQL.hs``.
