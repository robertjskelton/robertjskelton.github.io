---
layout: post
title:  "rskelton.com Tech Stack Details"
date:   2018-04-11 14:05:14 -0400
categories: tech
---

This blog, hosted at [rskelton.com](rskelton.com), is one of the many iterations of Robert Skelton's personal blog. Over the years, it has been hosted at [robertjskelton.blogspot.com](https://robertjskelton.blogspot.com) , robertjskelton.com (dead), and skelton.co (dead). I have hosted it using WordPress on Digital Ocean, Github Pages, a Static AWS S3 bucket, and now this current iteration is my favorite. This site is here to stay, finally. This site also merges content from citrusrenovations.com (defunct home renovation blog) and retirengineering.com (defunct financial blog), both of which I hosted using WordPress on DigitalOcean.

I tried setting up rskelton.com using a Highly Available (HA) WordPress install on AWS. I use AWS for job full time, so this would be good experience. The problem is, it's really expensive to have a HA install, $70/mo or more. I didn't want to pay that much.

----

rskelton.com currently uses the following technologies, and drew inspiration from [Joe Hendrix's Github Page](https://hendrixjoseph.github.io):
* [Jekyll](https://jekyllrb.com/), specifically [jekyll-now](https://www.jekyllnow.com/). Jekyll is an awesome framework that turns markdown into a website. It takes a little while to get used to it, definitely more complicated than Wordpress, but worth the time to learn it.
* [Github pages](https://pages.github.com/), which automatically runs and hosts the jekyll markdown code
* Github for the code for the site. Open Source, public repo, available [here](https://github.com/robertjskelton/robertjskelton.github.io). For new posts, I just create the post locally on my laptop, I can use "jekyll serve" to preview the website changes in localhost:4000, and then simply push my changes to my repo and they appear on [rskelton.com](rskelton.com) within seconds.
* [Route 53](https://aws.amazon.com/route53/) in AWS, this is my DNS. I pay a small amount per lookup, less than $1/month.
* [Cloudflare](https://www.cloudflare.com) for SSL. Github pages does SSL if you use their website name (robertjskelton.github.io) but since I used a custom domain, that isn't supported. Cloudflare provides a [simple way](https://blog.cloudflare.com/secure-and-fast-github-pages-with-cloudflare/) to fix that.
* [Disqus](https://disqus.com/) for comments
* [Google Analytics](https://analytics.google.com) for Analytics
* [Google Adsense](https://www.google.com/adsense) for ads

----

I have also run/still run the following websites:
* [Beer Tasting Brevard](beertastingbrevard.com) - a beer tasting company website that I started. Hosted with an S3 bucket and Route 53 on AWS, using the Instagram API to pull new images from [Instagram](https://www.instagram.com/beertastingbrevard) so that I never have to manually update the website.
* [Robert's Epiphone Valve Jr Mods](http://robertsvalvejrmods.blogspot.com) - Electrical Engineering undergrad project for a course, I mad a bunch of modifications to a guitar amp.
* [Old Travel Blog](http://robertandashleightakeeurope.blogspot.com) - Hosted with Blogspot, a Europe travel blog with my ex-girlfriend.
