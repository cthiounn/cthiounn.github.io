---
layout: post
title:  "Installing Jekyll with Github!"
date:   2021-07-04 20:32:27 +0200
categories: jekyll update
---

## Create a repo with github

## Installing Ruby, RubyGem and Jekyll

1. Download and install Ruby at [Ruby Lang][ruby-lang]
2. Git clone and launch RubyGem from [Rubygems git repo][rubygems]
{% highlight bash %}
ruby setup.rb
{% endhighlight %}
3. install Jekyll with Gem and checkout the [Jekyll doc][jekyll-site]

{% highlight bash %}
gem install bundler jekyll
{% endhighlight %}

## Create site, push and voilà !

{% highlight bash %}
jekyll new my-awesome-site
cd my-awesome-site
mv . /path/to/your/local/repo
git commit -am 'init' && git push
{% endhighlight %}

[ruby-lang]: https://www.ruby-lang.org
[rubygems]:   https://github.com/rubygems/rubygems
[jekyll-site]: https://jekyllrb.com/
