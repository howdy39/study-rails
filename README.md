# study-rails

## Rails
### 起動

```
bin/rails s
```

↓のやりかたでも実質一緒らしい

```
bundle exec rails s
```

### 雛形を作成

```
bin/rails generate scaffold user name:string address:string age:integer
bin/rails db:migrate
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

