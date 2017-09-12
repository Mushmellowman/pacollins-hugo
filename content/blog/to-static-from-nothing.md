+++
author = "Patrick A Collins"
categories = ["General"]
date = "2017-08-25T23:00:00-04:00"
description = "Who am I? What is this site? Why does this site exist? and How was this site created?"
featured = "ToStaticFromNothing.jpg"
featuredalt = ""
featuredpath = "date"
linktitle = ""
title = "To Static From Nothing"
type = "post"

+++

## Who am I and what is this site for?

Hello, and welcome to my website! My name is Patrick Collins, though I'm sure you
figured that out by now since its plastered everywhere. I am currently a Senior
at Kennesaw State University studying Music Education. I'm drawn to music, education,
technology, and all things Walt Disney (especially Walt Disney World), so you
will find that much of the blog here will consist of content relating to these,
in addition to some eclectic sprinklings throughout. This site will also house
various things I create, including original or arranged music, drill designs,
photography, and applications. My hope is that someone will find *some* value in
something that gets posted here, and if not, then oh well.

If you are interested in more about me, check out the [**About**](/about/) page.
If you are interested in contacting me for whatever reason, feel free to comment
on the bottom of a post or check out the [**Contact**](/contact/) page.

## Why did I create this site?

This website is the product of many years with me wanting to buy a domain name
and create a personal website. Since, at the time, I had no real purpose to
own a domain name, I refrained from purchasing one. Now, as I enter my final year
of undergrad, I felt it was time to get a more professional email address to use
on job applications. Since I have used Gmail for a while, I prefer the platform,
so decided to see if I could get an address that I deemed appropriate. After a decent
amount of time inputting various *address*@gmail.com, I had no success. Every one
of them was taken. I then began to toy with the idea of buying a domain name for
myself, and then just creating an email address from there. My email address could
be whatever I wanted it to be and would look more professional than having
*address*@gmail.com. So I then began my search for domain name that would give a
professional look to my email address.

## How did I create this site?

#### <center>Compare Domain Registrars</center>

|                  | 1&1   	      | GoDaddy 	 | Google Domains 	     | Porkbun   |
| ---------------- | ------------ | ---------- | --------------------- | --------- |
| New              | $0.99/yr     | $0.99/yr   | $12.00/yr             | $8.84/yr  |
| Renewal          | $14.99/yr    | $14.99/yr	 | $12.00/yr             | $8.84/yr  |
| Transfer         | $0.99/$14.99 | $7.99      | $12.00                | $8.84     |
| DNS              | Yes    	    | Yes   	   | Yes                   | Yes       |
| Email            | 1 Free       | $2.99/mo   | $5.00/mo</br>$50.00/yr| $2.00/mo  |
| Email Service    | 1&1          | Office 365 | GSuite                | Porkbun   |
| Email Forwarding | Yes          | No         | Yes                   | Yes       |
| WHOIS Privacy    | Free         | $9.99      | Free                  | Free      |
| SSL Certificate  | No           | No         | No                    | Yes       |

After searching the standard sites, such as GoDaddy, for pricing, I eventually
came across [1&1](https://www.1and1.com/) where I was able to register this domain,
pacollins.com, for a year at a grand total cost of of **$1.17**! Included with
the domain was a free email address via 1&1 Webmail and WHOIS Privacy. Honestly,
I didn't realize how cheap domain names are. To be fair, this was an introductory
price and in the future it will cost $16/year from 1&1, but all things considered,
it is pretty reasonable. I'm sure I will price it out again once I get to that
point, but I am speculating that I will move over to [Google Domains](http://domains.google.com)
since it will be $12/year with Google integration. That being said, the next step
was to set-up my email address.

{{< fancybox "date" "1and1webmail.jpg" "1&1 Webmail Interface" "Post" >}}

I just want to say that I was pleasantly surprised with 1&1's Webmail. The interface
is sleek and intuitive - two things that are very important to me in a service,
free or not. Honestly, if I wasn't so attached to Gmail, I wouldn't mind using it.
Nevertheless, I was able to very easily forward my address to my personal address
and then connect to use it as an alias. As for the email service itself, after
sending and receiving a few messages through various platforms, I found that the
service was quick with minimal delays receiving and sending emails. Now with my
email established, I had accomplished what I had originally set out to do - acquire
a more professional looking email address.

But, being a techie, I couldn't stop there. This domain needed to be used, since
I had it, for a personal website. The problem was:

1. **I didn't want to pay for hosting.** I bought the domain out of necessity, but
I don't *need* a website.
2. **I didn't want advertisements on my website.** I can't have the slightest
possibility of stray advertisements of questionable nature popping up on my site.
3. **I wanted to have autonomy with how the site is built, how it functions, and what
it looks like.** Easy manipulation of the source code is a must.
4. **I wanted to be able to easily work on my site offline.** This includes being able
to see new content *and* new features thought a fully functioning localhost site.
5. **Most importantly, I wanted something lightweight and simple.** I knew if it was
going to be cumbersome to edit the site, I wouldn't do it and I would end up wasting
a lot of my time establishing the site to just leave it unmaintained.

{{< fancybox "date" "hugo.jpg" "Hugo Static Site Generator" "Post" >}}

Since I knew I didn't want advertisements or to pay for hosting, that knocked out
the majority of services people typically use. It left mostly the blogging platforms
left. Also, I knew that, with a need for autonomy, those sites, such as WordPress,
Wix, SquareSpace, would limit my ability to do so. Unfortunately, I *do* enjoy the
ease of a Content Management System (CMS), so I was looking for something similar.
So with most of the standard places to host my site not meeting the standards I
needed, I eventually came across GitHub Pages. GitHub Pages gives free hosting with
the only caveat being that the site must be static. For what I was planning on doing,
this was no issue; it would be a little cumbersome, but not an issue. (As a side
note, if you dont own a domain, your url will be *username*.github.io.) So in order
to solve issue #5, I needed to find a CMS for static sites. I eventually came across
Hugo, which is a static site generator. Hugo gives the basic functionality of a
CMS (using the idea of templates), but compiles them into a static site. As an added
bonus, Hugo comes with a lightweight server that can compile the site in real time
for viewing. Hugo is lightweight as an 11MB executable that ties in with command
line. It even is supported by a host of themes to make set-up even easier. I ended
up going with "Future Imperfect," a Hugo port, by jpescador, of an HTML5Up Theme.
GitHub Pages was the solution to #1 and #2; Hugo was the solution to #3, #4, and #5.

With all of that done, in addition to some behind the scenes stuff with the theme,
the majority of the site is up and ready to go. If you had no itention on personalizing
the sylistic aspects of the theme, you could easily be up and ready *with* content
in less than 24 hours.

## Your Thoughts

What do you think about creating a website using Hugo? Any questions? Would
you be interested in a guide digging more into how to use Hugo/GitHub Pages in a
less techincal manner than the documentation? Your feedback and interaction is
what makes this blog interesting for me and other readers, so please share your
thoughts below in the comments!
