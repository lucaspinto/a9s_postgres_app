# README

```
# start postgres
docker run -d -p 5432:5432 postgres

# install app dependencies and start the server
bundle
bundle exec rake db:setup 
bundle exec rails s
```

Open [http://localhost:3000/](http://localhost:3000/) in your browser.
