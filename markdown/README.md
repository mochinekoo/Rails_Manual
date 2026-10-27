#
* アプリを追加する
```rails new アプリ名```

* サーバーを起動させる
```rails server```

* 自動生成
```rails generate scaffold Note title:text body:text```
```rails generate scaffold_controller Note title:text body:text```

* データベース
```rails db:create```
```rails db:migrate```

* routes.rb
```ruby
Rails.application.routes.draw do
  root "home#index"
  get "up" => "rails/health#show", as: :rails_health_check
end
```
