# README

* Ruby version: 3.2.3


* Configuration
    run:
    # docker-compose up -d db cache
    # docker-compose build app jobs
    
    after start, run server with:
    $ rails s -b 0.0.0.0
    

* Database creation
    docker-compose run --rm app rake db:create db:migrate


