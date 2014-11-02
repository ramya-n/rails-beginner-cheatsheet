Rails Beginner Cheat sheet
=========================

A cheat sheet for Rails beginners, taking care of a lot of basic stuff and information. Aimed at helping beginners to look up stuff.

You can view this cheat sheet in all its "beauty" here: http://pragtob.github.io/rails-beginner-cheat sheet/

As opposed to other cheat sheets it isn't necessarily aimed at brevity, but comprehensibility. It also takes care of the very basics, like cd on the command line, that beginners sometimes forget or confuse.

Originally created for my RailsGirls project group, as it became apparent that it would be cool to be able to have a place to look up the common stuff.

How to contribute?
==================
Contributions are very welcome. Just go ahead and open a pull request. Be it corrections, new content or some styling (I haven't exactly mastered styling... yet).

Any contribution will be repaid with eternal gratitude!

Here's how you can make changes.

Fork the repository to your own GitHub account.

Download the project:

```
$ git clone git@github.com:MyGitHubAcoount/rails-beginner-cheatsheet.git
$ cd rails-beginner-cheatsheet
```

It is best to create a new branch to contribute (not necessary though):

```
$ git checkout -b my-new-branch
```


Make your changes.

Commit and push to the remote repository:

```
$ git commit -am "some helpful comment"
$ git push origin my-new-branch
```

Make a pull request (when you check the repository out online at github you should see a big green button to make a pull request shortly after you pushed the branch).

Get the site running locally
============================

To get the site running locally (for development/contribution or trying it out) do the following (after you cloned etc. as described above):

```
bundle install
jekyll serve
```

Now you can visit http://0.0.0.0:4000/ to see the website locally! Yay you!
