# Day 51
## __3/1/2021__

## What is SQL injection?
SQL injection is a form of malicicious database attack in which SQL statements are placed in the database. Without proper data sanitation, it's possible for SQL to execute the injected statements and create a lot of damage and lost data.

## What are 3 methods SQL injection can be done by?
SQL injection can be done through any piece of data which is processed by the back end. This can be through user input via a form, cookie modification, and HTTP headers.

## How can we detect and sanitize SQL injection attacks?
There are third party tools that check incoming data for potential attacks, such as the one we use, Dapper. It's also wise to do damage mitigation of a potential successful attack by following the principle of least privilege and allowing an application only the permissions it needs to operate.