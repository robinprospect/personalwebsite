# Change It Up

## Setup

Close this repo to your computer and open it in your terminal (Linux or OSX).

```sh
cd place/where/you/keep/projects
git clone git@github.com:robinprospect/changeitup.git
cd changeitup
```

Ensure you have the Ruby programming language installed on your computer
(check with `ruby --version` in the terminal) and then run this command to
install Jekyll:

```sh
gem install github-pages
```

If it fails you may need to prefix the command with `sudo `.


## Running the local development server

So that we can see what our changes look like Jekyll includes a local
development server.

To run it run this command:

```sh
jekyll serve --livereload-port 9005
```

Now you can view a local version of the site in your browser at
[`http://localhost:3000`](http://localhost:3000).


## Writing new posts

The documentation for posts in Jekyll can be found [here](https://jekyllrb.com/docs/posts/).

Once you are happy with your changes we want to commit them and push the new
code to GitHub so they can compile and serve the website.

```
git add --all
git commit -m 'A short message detailing what has changed'
git push origin master
```

Within a couple of minutes the changes should be live!
