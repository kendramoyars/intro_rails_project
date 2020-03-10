Introduction
In this project, you'll get the opportunity to actually build a real rails application. It's not a trivially simple one either -- it's got a lot of wrinkles and things that you're not going to understand.

To be honest, you're kind of going into the deep end so don't worry if you don't understand what exactly you're doing in all the steps. The point here is to get familiar with the process of creating a Rails app, what things generally look like, and what you don't know. When you get to the end of this project, you can consider yourself remarkably persistent and resilient.

Because you'll be doing so much stuff that we haven't taught you yet, this is a good project to find a partner to work with on even though it's just following a tutorial.

Assignment
Follow the instructions atop the Google Homepage project to set up a Github repository for this project (of course you'll need to change the title).
Do the Jumpstart Lab's Blogger Tutorial sections I0 through I4. Pay attention to any error messages you get, both planned (because the tutorial walks you through a common error-guided workflow) and unplanned (likely for things like spelling errors). You'll see all these messages again and again when you're building Rails apps, so it's helpful to start getting familiar with which portions of the message you should pay attention to (and maybe put into Google if you can't figure out what caused it).
At the end of I3: Tags when you're attempting to delete your Article tags, you'll run into an error along the lines of "FOREIGN KEY constraint failed". You can solve this by enforcing Referential Integrity by applying the dependent: :destroy option for the has_many method in the right model. You can learn about it in This Entry of the Rails Guides
Here's a helpful gist with common Blogger problems if you're running into issues with routes, deleting, partials, and redirect_to.
If you're feeling ambitious, add in authentication in section I5.
If you're feeling very ambitious, try doing the final Extras section I6.
Don't forget to deploy your app to Heroku! Review Heroku deployment here.
Student Solutions
Solution by Kendra Moyars - https://github.com/kendramoyars