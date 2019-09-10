# Quiz: Active Record

???

## Active Record

?:

```ruby
class Car
end
```

To make use of ActiveRecord's built-in ORM methods for this `Car` class, which syntax is used?

( )
```ruby
class Car < ActiveRecord
end
```
(X)
```ruby
class Car < ActiveRecord::Base
end
```
( )
```ruby
class Car < ActiveRecord:Base
end
```
( )
```ruby
class Car > ActiveRecord::Base
end
```

?: Which of these methods are **NOT** inherited via its relationship to ActiveRecord?

( ) `.column_names` ( ) `.create` ( ) `.find` (X) None of the Above

?: To by any attribute, such as `make`, which method should be used?

( ) `.find` ( ) `.find_by_name` ( ) `.filter` (X) `.find_by`

?: Rake is a tool that is available to us in BASH that allows us to automate certain jobs?

( ) True (X) False

?: To build a Rake task, what file should be created?

( )`Rakefile.rb` ( )`Rake` (X)`Rakefile` ( )`.Rakefile`

?: Which syntax is used to define a Rake task?

(X)
```ruby
task :alert do
  puts "This is an important task"
end
```
( )
```ruby
task :alert
  puts "This is an important task"
end
```
( )
```ruby
task .alert do
  puts "This is an important task"
end
```
( )
```ruby
rake :alert do
  puts "This is an important task"
end
```

?: Which command in the terminal will return a list of available Rake tasks and their descriptions?

( ) `rake` ( ) `rake console` ( ) `rake ls` (X) `rake -T`

?: When using Active Record migrations, we no longer need SQL to create and change tables and their data.

(X) True ( ) False

?: To run a migration, which syntax is used?

(X) `rake db:migrate` ( )`rake db` ( )`rake db::migrate` ( )`rake migrate:db`

?: To write a migration to change a column name, which syntax is used?

( ) `add_column(table_name, column_name, type)`
( ) `column_change(table_name, column_name, type)`
(X) `change_column(table_name, column_name, type)`
( ) `update_column(table_name, column_name, type)`

???
