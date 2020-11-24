---
layout: post
title:  "rskelton.com Tech Stack Details"
date:   2018-04-11 14:05:14 -0400
categories: tech
---

This blog, hosted at [rskelton.com](https://rskelton.com), is one of the many iterations of Robert Skelton's personal blog. Over the years, it has been hosted at [robertjskelton.blogspot.com](https://robertjskelton.blogspot.com), robertjskelton.com (dead), and skelton.co (dead). I have hosted it using WordPress on DigitalOcean, Github Pages, a Static AWS S3 bucket, and now this current iteration is my favorite. This site is here to stay, finally. This site also merges content from citrusrenovations.com (defunct home renovation blog) and retirengineering.com (defunct financial blog), both of which I hosted using WordPress on DigitalOcean.

I previously set up rskelton.com using a Highly Available (HA) WordPress install on AWS. I use AWS for my job full time, so this was good experience. The problem is, it's really expensive to have a HA install, $70/mo or more. I didn't want to pay that much for just a blog, so I set about finding a new way to manage a blog.

----

rskelton.com currently uses the following technologies, and drew inspiration from [Joe Hendrix's Github Page](https://hendrixjoseph.github.io):
* [Jekyll](https://jekyllrb.com/), specifically [jekyll-now](https://www.jekyllnow.com/). Jekyll is an awesome framework that turns markdown into a website. It takes a little while to get used to it, definitely more complicated than Wordpress, but worth the time to learn it.
* [Github pages](https://pages.github.com/), which automatically runs and hosts the jekyll markdown code
* Github is where for the code for the site is hosted. It is all open source in my public repo, available [here](https://github.com/robertjskelton/robertjskelton.github.io). For new posts, I create a post locally on my laptop. I can use "jekyll serve" to preview changes in a browser at "localhost:4000", and then push my changes to my repo. After that, they appear on [rskelton.com](https://rskelton.com) within seconds.
* [Route 53](https://aws.amazon.com/route53/) in AWS, this is my DNS. I pay a small amount per lookup, less than $1/month.
* [Cloudflare](https://www.cloudflare.com) for SSL. Github pages does SSL if you use their website name (robertjskelton.github.io) but since I used a custom domain, that isn't supported. Cloudflare provides a [simple way](https://blog.cloudflare.com/secure-and-fast-github-pages-with-cloudflare/) to fix that.
* [Disqus](https://disqus.com/) for comments.
* [Google Analytics](https://analytics.google.com) for Analytics.
* [Google Adsense](https://www.google.com/adsense) for ads.
* [Mailchimp for Subscriber emails](https://blog.webjeda.com/jekyll-subscribe-form/) - 2.5 years later I added an email signup. 

----

I also own the following websites:
* [Robert's Epiphone Valve Jr Mods](http://robertsvalvejrmods.blogspot.com) - Hosted with Blogspot, this was an Electrical Engineering undergrad project, I made a bunch of modifications to a guitar amp and documented them on this site.
* [Europe Travel Blog](http://robertandashleightakeeurope.blogspot.com) - Hosted with Blogspot, this is a 2013 Europe travel blog. If I hadn't made these 2 blogs using Blogspot, I'm 100% sure I would have tried to change hosts 10 times and lost all my content over the last 5 years. Blogspot isn't fancy or pretty, but I'm glad I used it back then.

----

Former websites
* Beer Tasting Brevard - a beer tasting company website that I started. It was hosted using a static S3 bucket, AWS Cloudfront for SSL, and Route 53 for DNS. I also had some Javascript on the site that uses the Instagram API to pull new images from the Instagram I made for this page. This way, I never had to manually update pictures on the website, new images were automatically populated from Instagram posts.
* Citrus Renovations - WordPress blog hosted on a DigitalOcean droplet where I detailed home renovations. Most of that content has been migrated to this blog.
