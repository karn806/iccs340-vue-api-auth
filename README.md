u5780130

- Requires
  - rails 5.0.1
  - postgres
- run
  - rake db:create db:migrate
  - rake db:seed # run once to seed default user or use `rails c`
    - User.create!(email: "", password: "") # some email and password
  - rails s
- You can deploy to heroku
  - heroku create
  - git push heroku master
  - heroku rename SOMEOTHERNAME
