# 7Gonline

A multi-user blogging app in Rails: users write articles, tag them with
categories, and browse everything with pagination.

- Signup, login and logout with sessions and `has_secure_password`
- Articles and categories with a many-to-many join, plus admin-only category
  management
- Pagination with `will_paginate`
- Integration and controller tests for categories
- MySQL in production with credentials kept in Rails encrypted credentials

**Stack:** Ruby 2.7, Rails 6.1, Webpacker, SQLite / MySQL

## Run it

```bash
bundle install
bin/rails db:setup
bin/rails server
```

---

An early learning project from 2023, kept for reference and archived. My current work is on [my profile](https://github.com/gaganggoyal) and at [gagan.indiaoffers.in](https://gagan.indiaoffers.in).
