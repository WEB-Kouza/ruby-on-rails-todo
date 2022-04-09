## github
https://github.com/WEB-Kouza/ruby-on-rails-todo

bundle install
# ruby-on-rails-todo
## Ruby 2.6.3
## Rails 5.2.3

## 構築手順
1. rvm install 2.6.3
2. rvm use 2.6.3
3. gem -v
4. gem update --system
5. bundler -v
6. gem update bundler
7. gem install rails -v 5.2.3

## 移動(projectnameは置換してください。)
1. mkdir projectname
2. cd projectname

## rails環境構築
1. rails new . 

## git
1. git init
2. git add .
3. git commit -m "rails new"

##  gemfile追加コード
```
# Bootstrap4 and jQuery
gem 'bootstrap', '~> 4.3.1'
gem 'jquery-rails'
```

## gem file追加後
1. bundle install