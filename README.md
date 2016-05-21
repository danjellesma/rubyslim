## RubySlim Docker Image
Version `2.0`
Migrated to Alpine Linux image of `ruby-2.3.1-alpine`.

A slim ruby image based on Alpine Linux ready for Rails
- `MySQL`, `Postgres`, and `SQLite3` extensions
- Nodejs for Javascript runtime
- Bash for better shell experience
- TZData for timezone support
- Nokogiri gem fix

#### Database Driver Support
These libraries are installed in the container support Gem installations to support the following database types.
- PostgreSQL (pg)
- MySQL (mysql2)
- SQLite (sqlite3)
