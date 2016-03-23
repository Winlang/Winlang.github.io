---
layout: post
title:  "Using a custom domain with GitHub Pages"
date:   2016-03-23 10:54:23
categories: domain pages
tags: domain pages
image: /images/pic01.jpg
---
You can customize the domain name of your GitHub Pages site.

Quick start: Setting up a custom domain

There are three main stages to setting up a custom domain for your GitHub Pages site: choosing your custom domain and registering it with a DNS provider, setting up your pages site repository, and configuring your domain with your DNS provider.

About supported custom domains

If you're setting up a custom domain for your GitHub Pages site, choose a supported custom domain for the easiest setup and more support. GitHub Pages is designed to work with two types of custom domains: apex domains and subdomains.

Custom domain redirects for GitHub Pages sites

The type of pages site you're using determines how your site redirects custom domains.

Setting up your pages site repository

Before setting up your custom domain with your DNS provider you need to set up your GitHub Pages site repository by adding a CNAME file.

Setting up an apex domain and www subdomain

You can set up an apex domain and a www subdomain through your DNS provider and GitHub Pages' servers will automatically create redirects between them. For example, your site can be found at www.example.com or example.com.

Setting up an apex domain

To set up an apex domain, such as example.com, you must configure an ALIAS, ANAME, or A record with your DNS provider.

Setting up a www subdomain

To set up a www subdomain, such as www.example.com you must configure a CNAME record with your DNS provider.

Setting up a custom subdomain

You can set up a custom subdomain, such as blog.example.com, by creating a CNAME record through your DNS provider.

Troubleshooting custom domains

If your GitHub Pages site isn't loading at your custom domain, you may have an error in your GitHub repository setup or your DNS configuration.

 Contact a human

 from github.


{% highlight php %}
echo 'test';
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
