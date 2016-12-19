#### to run server and view live page locally
1. install bundler (from [bundler.io](http://bundler.io))
2. `cd` to main directory
3. `bundle install`
4. `bundle exec jekyll serve`
5. go to `localhost:4000`

#### To create a post:
1. `cd` into `_posts`
2. create markdown file with name in the form of: `year`-`month`-`day`-`posttitle`.md
3. open the post and another, similar, post that has been previously published that you expect to contain similar content
4. verify that the tags in your markdown match those in the previous post for style consistency
  - a common example is that code blocks for posts should be wrapped in `{% highlight <lang> %}` and `{% endhighlight %}` rather than the typical ```` ``` <lang> ```` and ```` ``` ```` (where you replace `<lang>` with the language), and that output of code blocks should be indented by 4 spaces. If you have doubt, check an existing post, and if that fails, ask @gkiar.
5. run locally when you're ready (instructions above) and verify you're happy with your content before pushing

#### To create and but not view in website or publish
1. if you wish to create a draft of a post but aren't ready to even view it in your local deployment yet and wish to commit it to the repo for safekeeping, you simply need to break the naming scheme of your markdown file in the posts directory. One simple example of this is replacing the `-` symbols with `_`, and the post will no longer appear in the website.
