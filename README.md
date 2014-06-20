#Fontello API Package for Laravel 
A simple module for Laravel in early status. 

##Usage
This package gives you the ability to use fontello api directly in your laravel application. 

###Basic Setup
Require this package in you composer.json 

`"derduesseldorf/fontello" : "1.1.1.0"`

After updating composer add the ServiceProvider to the providers in your app/config/app.php 

`"Derduesseldord\Fontello\FontelloServiceProvider"`

Add the Facade to the aliases in app/config/app.php 

`"Fontello" => "Derduesseldorf\Fontello\FontelloFacade"`

###Create basic directory structure

+ **config.json**  
the config.json will be placed in "public/assets/fontello"
+ **Css files**  
All css files will be placed in "public/assets/fontello/css"
+ **Font files**  
All font files will be placed in "public/assets/fontello/font"
+ **Temp folder**  
The temporary data will be placed in "public/uploads/"

**Make sure to setup "public/assets" and "public/uploads"**


