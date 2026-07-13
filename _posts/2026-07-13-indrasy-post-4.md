---
layout: post
title:  "This Website's Journey"
date:   2026-07-13
categories: systems website
---
I think I should start this blog by stating the obvious. **I am not a professional web designer.** So, creating this blog last week has been a journey.

From learning how to using GitHub Pages, to then struggling with the official GitHub Pages forums, and then lastly giving up on the said forums to go and look for another source of information, the creation of this site was a combination of me jumping through random hoops that I set for myself. 

I am quite familiar with the way websites function. I’ve hosted a couple ngenx sites in the past and have troubleshooted some Apache stuff as well. I have experience with PHP and HTML when designing the inner workings of a site. But never have I ever used Ruby.

Looking at the documentation for this service, I was totally stunned to see that they recommend users to use Ruby for the creation of this site. This language is totally foreign to me so I got lost really fast. The first version of the site was just a plain markdown page because that is all that I figured out.

I was reading these guides that are officially listed, which all mention the tool Jekyll for the creation process. I figured it was something built into GitHub Pages, but the more and more I read, the less and less I understood. Like people mentioned a “_pages” and “_site” directory that is created when the website is made, but none of that was appearing. Then the mention of Gemfiles caused me to become more confused since the step by step introduction guide hosted by GitHub never mentions creating such a thing in the first place.

So I was lost. Very lost. But then I decided to watch a video on how to create sites using Jekyll on GitHub Pages. Credit where credit’s due, [here](https://www.youtube.com/watch?v=fV01b0duZwU) is the link to the video guide I used. The video walks you through the basics of how to host the site locally then pushing it to GitHub Pages.

After I figured it out and pushed my local site to the main branch, I started to go and plan what this site will be about. I started creating this site because I wanted a blog, but I didn’t have much of a focus set in mind.

This is when I started considering scale. How wide did I want my reach to be, in a sense. What topics did I want to cover and how should I host them here? So I decided to classify topics by genre. 

I want to use this site to do two things: more personal discussions about hobbies and the such as well as more technical discussions on projects and research. Hence, this is why I decided on separating these topics by category. It is a simple solution that allows me to post both while separating them. On my off time, I plan to do some research on how I can separate the feed by topic, but for now that is a small issue. 

On a different side of scale, I also had to consider the features/dependencies of this site. With the resources that I am using, such as Jekyll, Ruby, and GitHub Pages’s gems, I realized very quickly that I needed to decide what tools this site would be using and make sure that everything works without conflict. For small context, gems are basically packages that are defined in a Gemfile to build an environment.

It took a bit to find versions of the minima gem that didn’t argue with GitHub Page’s gem lol. But, since my site is small and the scope of features is small, this thankfully isn’t much of a problem. It **IS** a consideration when thinking about scaling my website up. With more features, I need to plan around how to untangle the web of dependencies I add.

I’m sure none of this is revolutionary, but I did want to catalog this journey of mine. I am definitely certain that this Jekyll setup has infuriated people in the past, so even offering a resource such as the video above would help anyone who might struggle with this system in the future. Before I wrap up this post, I do have a couple of pieces of advice I want to mention as a head’s up for anyone that is planning to host a site on GitHub Pages for the first time.

**First**, use the official GitHub Pages documentation only as a resource, not a guide. It expects you as a user to be familiar enough with the service to understand how to set up the rest of the features after getting a basic site up and running.

**Second**, plan ahead. Most of my struggles on this site happened when I was tinkering with Ruby locally on my computer. For example, the version of the Jekyll gem that GitHub Pages uses doesn’t like building on certain versions of Ruby, such as the latest version as of this post: version 4.0.5. Considering these things prior to starting will eliminate a headache from forming later on.

In short, building a site on GitHub Pages wasn’t as easy as I thought it would be. Thankfully it wasn’t that bad, but it had its shares of ups and downs. I recommend that if you are going to do this process yourself, start with the video linked above. Thanks for reading!


<script src="https://giscus.app/client.js"
        data-repo="UluKami/ulukami.github.io"
        data-repo-id="R_kgDOTO1r4A"
        data-category="Q&A"
        data-category-id="DIC_kwDOTO1r4M4DAoJk"
        data-mapping="og:title"
        data-strict="1"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-input-position="top"
        data-theme="preferred_color_scheme"
        data-lang="en"
        data-loading="lazy"
        crossorigin="anonymous"
        async>
</script>
