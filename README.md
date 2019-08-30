## TimePass

TimePass is an open source social networking platform written in Ruby on Rails. Here is the blog post: [How to build a social network using Rails](https://medium.com/@sudharshanmuralidharaniyer/eb31da569233).

[![Heroku](http://heroku-badge.herokuapp.com/?app=TimePass&style=flat)](http://TimePass.herokuapp.com)

Do you want to see it in action? Here is a working version deployed to heroku [http://TimePass.herokuapp.com](http://TimePass.herokuapp.com)

### UPDATE

Since my cloudinary free tier hit a bandwidth overload. So had to switch to AWS. If you plan on deploying to production please set the AWS key and secret as environment variables. Or you can checkout the older version which uses cloudinary 
https://github.com/ammu0001/TimePass/tree/930b2f7c6a6eb6b442189dc6237765dbf16d461c

### UPDATE #2

Updated the Rails version to 5.0. Thanks to [@briankung](https://github.com/briankung) for the Pull Request. There are some more things to be upgraded which will be done shortly. Refer this for the list of changes to be done https://hashrocket.com/blog/posts/how-to-upgrade-to-rails-5.

### What it uses?

* [Ruby on Rails](https://github.com/rails/rails)
* [Bootstrap](https://github.com/twbs/bootstrap-sass)
* [Devise](https://github.com/plataformatec/devise)
* [Public Activity](https://github.com/chaps-io/public_activity)


### How do I get set up?

To set it up on your local machine here is what you need to do. Install Ruby & Rails. Clone this repo using the following command:

```
git clone https://github.com/ammu0001/TimePass
cd TimePass
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

This will create records with values from faker & populator gems. Also here are the test user credentials:

* email: test@TimePass.com
* password: password

### Pull Requests

* Fork this repo
* Make changes to code
* Send Pull Request

### Issues
If you find any issue with the app please do raise an issue here https://github.com/ammu0001/TimePass/issues

### License
This project is Licensed under the [GNU GPL V2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html). See  [LICENSE](https://github.com/ammu0001/TimePass/master/LICENSE) for more info.
##### SA90338669

##### SC15561127
