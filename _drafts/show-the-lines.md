---
layout: post
title:  "Show the lines"
date:   2018-07-08 14:58:00 +0800
categories: jekyll update
---

{% highlight ruby linenos%}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}

{% highlight python%}
print("Hello, world.")
{% endhighlight %}