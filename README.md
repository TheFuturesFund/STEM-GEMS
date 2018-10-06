Website for Baton Rouge STEM-GEMS, built by Futures Fund students.

This site is built with [Jekyll](https://jekyllrb.com/).

# Getting Started

To get started, first clone the site if you haven't already.
This will create a new folder with all of the code for the site on your computer.

```
git clone git@github.com:TheFuturesFund/STEM-GEMS.git
```

Use `cd` to navigate to the site.
To get the latest changes, use `git pull`.

You may need to create a merge commit.
To do that, use `ctl + X` to close the editor when it opens.

If you have merge conflicts, please grab an instructor to help you resolve them.

### Running the site

To run the site, make sure you have used `cd` to navigate the the site's folder in your terminal.
Then, run the following:

```
bundle install
jekyll serve
```

The site should start up and then you can visit it at [localhost:4000](localhost:4000).

### Pushing your code

Once you have made the changes you want, you will need to push your code to share it with your team.

First, make sure you have used `cd` to navigate to the folder for the site in your terminal.

Next, you need to stage your changes:

```
git add .
```

Use `git status` to make sure all of the files you want are added.

Next, you need to create a commit with your changes:

```
git commit -m 'type a short message describing your work here'
```

Once you have committed, you can push the changes up to GitHub like this:

```
git push
```

If your changes are rejected, you may need to pull first and create a merge commit.
Run `git pull` and then use `ctl + X` to leave the nano editor.
If you have merge conflicts, please ask an instructor for help resolving them.
