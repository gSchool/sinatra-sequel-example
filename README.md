# Sample App w/ Database

## Create your local databases:

    psql -U yourusername -d postgres -f scripts/create_database.sql

## Migrate your databases

    sequel -m move-bd postgres://user:password@localhost/birds_development
    sequel -m move-bd postgres://user:password@localhost/birds_test
