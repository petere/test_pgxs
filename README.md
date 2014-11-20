# Tests for PostgreSQL PGXS

This is a test suite for the PostgreSQL extension building
infrastructure, documented at
<http://www.postgresql.org/docs/devel/static/extend-pgxs.html>.

To run the tests, run

    ./runtest

To test the different "vpath" variants, run one of

    ./runtest intree  # default
    ./runtest make_f
    ./runtest vpath

The tests will run `make installcheck`.  To make that work, you might
need to set `PATH` and/or `PGPORT` to point to a running PostgreSQL
instance.
