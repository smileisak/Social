# Social Network for securinets members 

This is the open source social network project for Securinets

    $ cd /tmp
    $ git clone git@github.com:smileisak/social
    $ cd social
    $ cp config/database.yml.example config/database.yml
    $ bundle install
    $ bundle exec rake db:migrate
    $ bundle exec rake db:test:prepare
    $ bundle exec rspec spec/

If the tests don't pass, it means there may be something wrong with your system. If they do pass, then you can debug your code by comparing it with the reference implementation.
