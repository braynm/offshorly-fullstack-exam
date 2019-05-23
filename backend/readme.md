# Backend

Create http restful API using NodeJS. Please **do not** use any web framework E.G.(Express, Koa)

### TODO:

#### Create endpoints

- Create counter item
- Delete counter item
- Update counter item
- Get counter list

#### Data Storage

Create a database and table for storing the data.

```
-- Create database
create database fullstack_exam;

-- Create counter table
create table counter(
 id serial primary key,
 amount integer
);
```

Please add tests. Use `mocha` test framework or something similar.

## Plus points

- Working Demo (deployed on Heroku or something similar)
