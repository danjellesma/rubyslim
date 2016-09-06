## RubySlim Docker Image

#### Versions
`2.3.1`, `2`, `latest` : `ruby-2.3.1-alpine`.

#### Description
A small Ruby image based on Alpine Linux ready for Ruby on Rails
- `MySQL`, `Postgres`, and `SQLite3` system extensions installed for easy use with respective gems.
- Nodejs installed for Javascript runtime
- Bash for better shell experience
- TZData for timezone support
- Nokogiri / Alpinegem fix

#### Database Driver Support
These libraries are installed in the container support Gem installations to support the following database types.
- PostgreSQL (pg)
- MySQL (mysql2)
- SQLite (sqlite3)
