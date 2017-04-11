# Sample Ruby on Rails App
This is a playground for Ruby on Rails!

## Versions
  * Rails: 5.0.2
  * Ruby: 2.4.0

## Dependencies
  [PostgreSQL 9.6](http://postgresapp.com/)

  Go to bash profile:

  ```
    atom ~./bash_profile
  ```

  Add these lines to the bottom of your bash profile:

  ```
    export PATH=$PATH:/Applications/Postgres.app/Contents/Versions/9.4/bin

    export PGHOST=localhost
  ```




## Getting Started

### Terminal: Basic Setup
  Start the rails server
  ```
    rails s
  ```
  Open a new tab: Start the rails console
  ```
    rails c
  ```
### Terminal: LiveReload
  This app uses a gem called 'guard-livereload'.

  To enable live reload in Chrome (open a new tab in Terminal):

  1.  Enable Chrome LiveReload Plugin
  2.  In the Terminal window:

    ```
      guard

    ```
