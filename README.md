## SocialBook

SocialBookis an open source social networking platform written in Ruby on Rails. 



### What it uses?

* [Ruby on Rails 4.1.6](https://github.com/rails/rails) 
* [Bootstrap](https://github.com/twbs/bootstrap-sass)
* [Devise](https://github.com/plataformatec/devise)
* [Public Activity](https://github.com/chaps-io/public_activity)


### How do I get set up?

To set it up on your local machine here is what you need to do. Install Ruby & Rails. Clone this repo using the following command:
  
```
git clone https://github.com/deepaksabat/SocialBook
cd SocialBook
```
Then resolve dependencies using bundler:

```
bundle install
```

Run Migrations:

```
rake db:migrate
```

Run rails using

```
rails server
```

### Populate Mock data
To test the app with mock data by running the following rake task:

```
rake fill:data
```








### Pull Requests

* Fork this repo 
* Make changes to code
* Send Pull Request


