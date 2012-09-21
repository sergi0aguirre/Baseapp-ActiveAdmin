Welcome to the Baseapp-ActiveAdmin wiki!


This is an application that merges two powerful tools,  [Baseapp](https://github.com/renderedtext/base-app ) and [ActiveAdmin](https://github.com/gregbell/active_admin). As we know Baseapp provides a simple app with signup ,  login , login with facebook, user settings section, an so on. In the other hand we have ActiveAdmin, that is a cool interface for the administration area, with a single command we can have the full CRUD for any model in our app. Both tools are strongly open and we can easily customize everything.


So merging these tools could give us an app running in a few minutes.


# App Demo
   
   We have an app runnig at Heroku:
   	http://baseapp-ativeadmin.herokuapp.com/
   you could singup and check the baseapp work
   
   For ActiveAdmin  go to :
   http://baseapp-ativeadmin.herokuapp.com/admin

   user:admin@example.com
   pass:password	

   *** All Features are ready to work, except fblogin, u have to setup your app keys by yourself

# Installation
  First clone this repository

   Install Bundler
   `gem install bundler`
  
   Install all gems required

   `bundle install`

#  Create database and run migrations

    `rake db:create`
   
    `rake db:migrate`

#  Run the app
     `rails s`



#Customization

   We could customize almost everything, just take a look of each documentation:

   [Baseapp](https://github.com/renderedtext/base-app )

   [ActiveAdmin](https://github.com/gregbell/active_admin)
  
  

  

    