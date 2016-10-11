---
title:  "Welcome to my blog!"
date:   2016-10-11 22:49:00
categories: [personal]
tags: [personal]
---

Hi!
The motivation of this post is have an example of all that is possible in a jekyll post.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Including images and resources:

Including an image asset in a post:

... which is shown in the screenshot below:
![My helpful screenshot]({{ site.url }}/assets/screenshot.jpg)

Linking to a PDF for readers to download:

... you can [get the PDF]({{ site.url }}/assets/mydoc.pdf) directly.

Code

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }s
  end
end
{% endhighlight %}

or

``` ruby
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
```

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
