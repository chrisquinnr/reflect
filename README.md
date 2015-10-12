# Reflect

A sever-side Meteor project which repsonds to all HTTP requests by sending back whatever GET requests or POST body you've submitted.

Useful for debugging http ops in other projects, so as you can see exactly what you're sending out of your application.

It's simple to add mock HTTP responses if you want to, for more information see http://iron-meteor.github.io/iron-router/#creating-routes.

## Use

Clone this repo, jump into the new directory and run `meteor`. 

>Remember you can use `meteor -pXXXX` to specify a different port for this run on if you've already got other Meteor apps running.

Then, within your app, using the `http` package, submit your HTTP calls as normal, and log out the response. The response should contain whatever parameters or data you've supplied.
 
 