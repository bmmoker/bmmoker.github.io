---
title: "The Journey"
date: 2019-08-14T03:52:17Z
menu: "Posts"
---

# The Journey

## The first leg

The initial set up of the site involved using a [DigitalOcean](https://www.digitalocean.com/) droplet (here is my [referral code](https://m.do.co/c/e7cce98bebca) for $50 over 30 days). From there I used a Nginx web sever and [Ghost](https://ghost.org/) as the main blogging application. It took my about 2 days to fully set it up after work and I was able to edit the  background and create a few posts and tabs. This was way back in February and was pretty seamless. This decision was made as a quick and easy way to get a site up and running. Unfortunately I found myself liking the under the hood set up and once ghost was up I found that I did not know enough about handlebars.js and didn't like the documentation that was out there. (_full disclosure: this is a fly by the seat of my pants situation and there is ***A LOT*** that I do not know about what I attempt to do. But that's the fun part_)

Below is essentially me through this entire process and going forward:

![Me trying to learn this stuff](/post/images/community_chaos.gif)

## The second leg

So there it was...a functional website with no urges to write or even explore what I could do to customize it. A few months later I started reading about [SSgs](https://www.staticgen.com/), or static site generators, and using Ghost's latest version to serve content quicker. This led me down the rabbit hole of trying to learn about the [JAMstack](https://jamstack.org) and how that may be the future of the web. Piquing my interest, I found an [article](https://ghost.org/blog/jamstack/) about using ghost with this JAMstack. Doing some more searching I saw [Gatsby.js](https://www.gatsbyjs.org/) pop up a few times. Luckily for me I ran it by a more experienced coworker who turned me on to this [article](https://brycewray.com/posts/2019/07/why-staying-with-hugo/) where Gatsby might be tough if you don't know JS, which I really don't. That article (along with my coworker) recommended Hugo. (_Coincidentally I mentioned Hugo to said coworker but didn't really know what it was so  it was quickly forgotten_)

Hugo was not the easiest to set up by any means. I still have the droplet from DO and, since I am navigating unknown waters, decided to install it there. Maybe this was part of the problem in the first place. But I kept working at it, thorough numerous rollbacks (_seriously, like 3-4 full rollbacks_) where it was too late in the night to venture down a new path. So I took note, rolled back, and started there the next day. Updating Hugo was a pain since I was installing version 0.16 instead of the latest which is 0.53 I think. I found some solace with this [article](https://computingforgeeks.com/how-to-install-hugo-on-ubuntu-18-04-lts/) to change the version number to 53 to remove an error near line 2. Took me forever to spin up the hugo site. Finally I was able to get that working after the update and was able to push it to GitHub.

The last part was [Netlify](https://app.netlify.com/). Which I heard was pretty good for deploying sites and connects right into github to push changes immediately. However, even this kept failing. An error with accessing the public folder on the repo. Had to change the path in .gitmodules to the https path instead of ssh..silly me.

But it worked and here we are!

## Conclusion

Don't get me wrong, the Ghost site worked and even came with a nice app to make publishing easier. Maybe a little too easy. The initial reason that I wanted to start a website was to see if I could and I thought enough time had passed where any experience I had (_took a class in college once_) had dwindled to the point where it would not affect how I viewed new ideas. So far so good, I would recommend again and who knows I might even do it. It's not the easiest and kind of easy to mess up but the reward is definitely worth it. The experience with Hugo, although frustrating and caused some long nights, was enjoyable It is a little more technical, which is a little more motivating. Now comes the hard part, creating the content.
