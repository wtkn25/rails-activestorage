# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

# 追記分
## ActiveStorageの追加

```
rails active_storage:install
```

## 使用例

```
post = Post.first
post.image.attach(io: File.open('./public/sample.png'), filename: 'sample.png')
```