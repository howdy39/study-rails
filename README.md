# study-rails
[現場で使える Ruby on Rails 5速習実践ガイド](https://book.mynavi.jp/supportsite/detail/9784839962227.html)


## Rails
### 起動

```
bin/rails s
```

↓のやりかたでも実質一緒らしい

```
bundle exec rails s
```

### console 起動

```
bin/rails c
```

### 雛形を作成

```
bin/rails generate scaffold user name:string address:string age:integer
bin/rails db:migrate
```


### ルーティング
config/routes.rb

#### ルーティングを表示

```
bin/rails routes
```


## PostgreSQL
### 起動

```
brew services start postgresql
```

### 停止

```
brew services stop postgresql
```

## DB
### DB作成
※config.dabase.yml をみている

```
bin/rails db:create
```

