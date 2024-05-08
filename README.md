# j2d2.github.io

```
bundle exec jekyll serve
# Pass the --livereload option to serve to automatically refresh the page with each change you make to the source files: 
bundle exec jekyll serve --livereload


```

Running locally
Before you start make sure you have Ruby and the gems for Jekyll installed locally. You can find out how to do that here.

Clone your resume repository locally (if you haven't already)
cd [your-repository-name]
bundle install
bundle exec jekyll serve
Open your browser to http://localhost:4000
Any changes you make will automatically build and you will be able to see these by refreshing your browser.

Note: You will need to re-run bundle exec jekyll serve to see changes made in _config.yml.



This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](https://jekyllrb.com/)

You can find the source code for Minima at GitHub:
[jekyll][jekyll-organization] /
[minima](https://github.com/jekyll/minima)

You can find the source code for Jekyll at GitHub:
[jekyll][jekyll-organization] /
[jekyll](https://github.com/jekyll/jekyll)


[jekyll-organization]: https://github.com/jekyll

# Jekyll Minima Post Example
```
---
layout: post
title:  "Welcome to Jekyll!"
date:   2018-10-23 13:02:25 -0700
categories: jekyll update
---
```
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

```
{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}
```

```
{% comment %}
Might you have an include in your theme? Why not try it here!
{% include my-themes-great-include.html %}
{% endcomment %}
```

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
