# Meteor.js-Task-List

Terminal for creating login and registration form
> meteor add accounts-ui  accounts-password 
 
 insecure package added by default. This is the package that allows us to edit the database from the client.
 It's useful when prototyping, but now we are taking off the training wheels. 
 To remove this package, go to your app directory and run:

>meteor remove insecure

If you try to use the app after removing this package,
you will notice that none of the inputs or buttons work anymore. 
This is because all client-side database permissions have been revoked. 
Now we need to rewrite some parts of our app to use methods.


 the task list will be empty. Without the autopublish package, 
 we will have to specify explicitly what the server sends to the client. 
 The functions in Meteor that do this are Meteor.publish and Meteor.subscribe.
>meteor remove autopublish
