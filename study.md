# Rails as an API Study

Use your favorite search engine and the provided readings to research and answer
the following questions (no prior knowledge is expected).

In your answers, be sure to cite any relevant sources you consulted in your
search. We ask you to write answers in your own words in order to see how you
process what you've read. Please do not answer with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

Please note:

-   Many of the readings will mention the "view" layer. We won't be covering the
    view layer in this program.
-   We'll use our [rails-api-template](https://github.com/ga-wdi-boston/rails-api-template)
    repository as the basis for our rails applications.
    This template excludes the "view" layer.

## Required Readings

-   [Starting Ruby on Rails: What I Wish I Knew | BetterExplained](http://betterexplained.com/articles/starting-ruby-on-rails-what-i-wish-i-knew/)
-   [Intermediate Rails: Understanding Models, Views and Controllers | BetterExplained](http://betterexplained.com/articles/intermediate-rails-understanding-models-views-and-controllers/)
-   [Getting Started with Rails — Ruby on Rails Guides](http://guides.rubyonrails.org/getting_started.html)
-   [The Rails Command Line — Ruby on Rails Guides](http://guides.rubyonrails.org/command_line.html)
-   [Rails Routing from the Outside In — Ruby on Rails Guides](http://guides.rubyonrails.org/routing.html)
-   [Action Controller Overview — Ruby on Rails Guides](http://guides.rubyonrails.org/action_controller_overview.html)

## Define Model Responsiblities

In your own words, define what the responsibilities of the model layer are in
Rails.

```md
Models handles the data. Objects in Ruby are defined using classes that contain both data and methods. Model holds our database and treats them as objects. Model respond to the user action through controller. We store our code in model that is related to our database, and then model returns results back to the controller and controller back to the view layer.




```

## Define Controller Responsiblities

In your own words, define what the responsibilities of the controller layer are
in Rails.

```md
Browsers communicate with controller that is guided by the user. Controller is responding to events trigered by user actions through browser. Controllers decide what it is going to happen based on those user actions. Those changes also known as user actions will invoke changes on the model and the view layer.
```

## Define Router Responsiblities

In your own words, define what the router does in Rails.

```md
Once browser make a request (triggered by user actions) then the web server receives that request. The web server uses routes to find out which controller to use. In other words, Rails router recognizes URL and matches them with controller's action.
```

## The Request-Response Cycle in Rails

Starting with a client making a GET request to a particular URL, describe how
the parts of Rails interact to produce and send a response.

```md
Once a client makes a GET request, it is received by web server that asks router to match controller action. Controller action is triggered by the user through browser. Web server then uses the dispatcher to create new controller that calls the action and pass parameters. 
```
