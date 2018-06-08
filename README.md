# Chat Bot

<br />

## Reference
### 只要有心，人人都可以做卡米狗
https://ithelp.ithome.com.tw/users/20107309/ironman/1253

<br />

## Environment & Tools

* Ruby on Rails
* PostgreSQL
* Heroku
* Line Messange API

<br />

#### 資料庫搬移
local
```
rails db:migrate
```

heroku
```
heroku run rake db:migrate
```

#### Show Heroku Logs
```
heroku logs -t
```

#### database command
```
rails db:drop
rails db:create
rails db:migrate
```
