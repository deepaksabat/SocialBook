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

### Screenshots
![index](http://s33.postimg.org/oe6ovz0kv/Screenshot_from_2016_06_02_15_30_38.png)
![home](http://s33.postimg.org/izr02nl4f/Screenshot_from_2016_06_02_15_28_10.png)
![profile](http://s33.postimg.org/jonql20mn/Screenshot_from_2016_06_02_15_29_13.png)
![post](http://s33.postimg.org/5hv4ncjhr/Screenshot_from_2016_06_02_15_28_56.png)
![find_friends](http://s33.postimg.org/jzsseprqn/Screenshot_from_2016_06_02_15_29_40.png)






### Pull Requests

* Fork this repo 
* Make changes to code
* Send Pull Request


