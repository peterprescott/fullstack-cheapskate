# README

You want to change the world. You want to solve a problem.
You want to use your tech skills to empower people to do good things.
There should be an app for that--except somehow there isn't.
So you're gonna find some friends, pitch your idea, and build something.

But you want them to start running straight away. 
So it needs to be open, so they can clone the repo without permissions.
And containerized, so they can run the thing without too much faff.
Then once you've built  it, it needs to be able to run forever, for free.

So I'm thinking a backend Flask app running on PythonAnywhere.
With a SQLite database file you can just copy without thinking too hard.
And a frontend hosted on Netlify.
And since I'm a data scientist, let's also have a Jupyter notebook or two.
Which you can plug into the database to interrogate it however you like.

So backend, frontend, data-science notebooks. 
These three should each have their own Git repos.
And then in this fullstack repo we treat them all as submodules.
And then use `docker compose` to get them all running locally.
