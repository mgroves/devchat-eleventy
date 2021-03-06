---
layout: layouts/post.njk
title: >
  213 JSJ Developer Evangelism with Greg Baugues
date: 2016-05-25 07:00:15
episode_number: 213
duration: 55:47
audio_url: https://media.devchat.tv/js-jabber/JSJ213DeveloperEvangelism.mp3?rss=true
podcast: js-jabber
tags:
  - js_jabber
  - podcast
---

### Check out [Newbie Remote Conf](https://allremoteconfs.com/newbie-2016)! July 13-15, 2016

&nbsp;02:16 - Greg Baugues Introduction

- [Twitter](https://twitter.com/greggyb)
- [GitHub](https://github.com/GregBaugues)
- [Blog](https://blog.baugues.com/)
- [Twilio](https://www.twilio.com/)
  - [Ruby Rogues Episode #258: Twilio with Greg Baugues](https://devchat.tv/ruby-rogues/258-rr-twilio-with-greg-baugues)
    02:41 - Developer Evangelism04:23 - Evangelism at [Twilio](https://www.twilio.com/)
- [Jeff Lawson](https://twitter.com/jeffiel)
  07:05 - [“Evangelism”](https://en.wikipedia.org/wiki/Evangelism)10:56 - Getting the Word Out
- [SIGNAL](https://www.twilio.com/signal)
  13:28 - Keeping Up-to-Date
- [Greg Baugues: Devs and Depression](https://baugues.com/depression)
  18:28 - Skills to Have as an Evangelist

1. Technical Credibility
2. Patience
3. Empathy
4. Hustle
   21:21 - Getting Help From Companies25:39 - Handling Larger-scale Issues27:15 - Building an Evangelist Team29:44 - Panelist Experiences with Evangelism&nbsp;Picks

- [Brené Brown: The power of vulnerability](https://www.ted.com/talks/brene_brown_on_vulnerability?language=en#t-410656) (Aimee)
- [Udi Dahan: The Fallacy Of ReUse](https://udidahan.com/2009/06/07/the-fallacy-of-reuse/) (Aimee)
- [Calendly](https://calendly.com/) (Chuck)
- [Gravity Forms](https://www.gravityforms.com/) (Chuck)
- [Trello](https://trello.com/) (Chuck)
- [Slack](https://slack.com/) (Chuck)
- [Zoom](https://zoom.us/) (Chuck)
- [Talky.io](https://talky.io/) (Greg)
- [SIGNAL](https://www.twilio.com/signal) (Greg)
- [The Tim Ferriss Show](https://fourhourworkweek.com/podcast/) (Greg)
- [Billions](https://www.imdb.com/title/tt4270492/) (Greg)

### Transcript

**_[This episode is sponsored by Frontend Masters. They have a terrific lineup of live courses you can attend either online or in person. They also have a terrific backlog of courses you can watch including JavaScript the Good Parts, Build Web Applications with Node.js, AngularJS In-Depth, and Advanced JavaScript. You can go check them out at FrontEndMasters.com.]_**

**_[This episode is sponsored by Hired.com. Every week on Hired, they run an auction where over a thousand tech companies in San Francisco, New York, and L.A. bid on JavaScript developers, providing them with salary and equity upfront. The average JavaScript developer gets an average of 5 to 15 introductory offers and an average salary offer of $130,000 a year. Users can either accept an offer and go right into interviewing with the company or deny them without any continuing obligations. It’s totally free for users. And when you’re hired, they also give you a $1,000 bonus as a thank you for using them. But if you use the JavaScript Jabber link, you’ll get a $2,000 bonus instead. Finally, if you’re not looking for a job and know someone who is, you can refer them to Hired and get a $1,337 bonus if they accept a job. Go sign up at Hired.com/JavaScriptJabber.]_**

**_[Let's face it. Bookkeeping is hard and it's not really what you're good at anyway. Bench.co is the online bookkeeping service that pairs you with a team of dedicated bookkeepers who use simple, elegant software to do your bookkeeping for you. Check it out and get your free trial today at Bench.co/JavaScriptJabber for 20% off today. They focus on what matters most and that's why they're there. Once again that's Bench.co/JavaScriptJabber.]_**

**CHUCK:&nbsp;** Hey everybody and welcome to episode 213 of The JavaScript Jabber Show. This week on our panel we have Aimee Knight.

**AIMEE:&nbsp;** Hello.

**CHUCK:&nbsp;** Dave Smith.

**DAVE:&nbsp;** Hello.

**CHUCK:&nbsp;** I'm Charles Max Wood from DevChat.tv. And I'm just going to shout out really quickly about Newbie Remote Conf. It's going to be in July, middle of July. It's the 14<sup>th</sup> through the 16<sup>th</sup>. So, if you're new and you want some pointers, some coaching, and it's all remote from real awesome experts, go check it out. We also…

**AIMEE:&nbsp;** Love it. Woohoo! Sorry, that's exciting. [Laughs] Okay, carry on. I'm sorry.

**CHUCK:&nbsp;** No, it's fine. [Laughs] we also have a special guest this week and that's Greg Baugues.

**GREG:&nbsp;** Hello.

**CHUCK:&nbsp;** Do you want to introduce yourself?

**GREG:&nbsp;** Sure. My name is Greg Baugues. I live in Chicago and I serve on the developer evangelism team for a company called Twilio that's based mostly out in San Francisco.

**CHUCK:&nbsp;** Nice. We actually talked to you about Twilio on Ruby Rogues a week or two ago. So yeah, we'll put a link to that in the show notes.

**GREG:&nbsp;** That was a lot of fun. Thanks for having me again.

**CHUCK:&nbsp;** It was. This week we're going to be talking about developer evangelism which is an interesting topic in and of itself. And I think whenever I talk to people about this topic just in passing, people [either] don't understand what it is or they're just like, “Eh, I don't really want to be a salesperson.” So, do you want to give people an idea about what developer evangelism is? Because I think it does things for the developer community that people don't really understand.

**GREG:&nbsp;** Yeah. I would love to. And I think it's probably good to preface this by saying I wholeheartedly understand the confusion around it. I think that's due in part to the fact A, developer evangelism is a very new profession. It only really makes sense for companies that are selling or have a product that's consumed by developers. Right? So, that's a fairly new phenomenon, especially becoming super common. But the second reason is that the job varies drastically from one program to the next. So, I can speak a little bit about broader industry trends but for the most part the only thing I can really speak super authentically on and authoritatively on is what it's like being a developer evangelist at Twilio.

But I do think there's a lot of confusion because not only do you have developer evangelists, you also have developer advocates. You have, they'll call them Dev Rels or developer relationships. And you have even community managers and there's not even standardization across the industry as to what job titles mean what. So, an evangelist at one company would be called an advocate at another. That you can have evangelists at two different companies and their jobs look totally different.

So, let me tell you a little bit about what it's like at Twilio, what I do. So, Twilio is a cloud communications company. What we're most known for is having APIs that make it really easy for developers to send and receive text messages and place and receive phone calls. And so, just a few lines of code in say Node but really, it's a RESTful API. But we have helper libraries for just about every language that's out there. Just a few lines of code, you can send and receive text messages, place and receive phone calls. Over the last year we've been rolling out more products for communication. So, we now have video chat. We now have IP messaging or just text-based chat and SDKs to be able to deploy that across a bunch of different platforms. But generally speaking we're a communications company. And our product is built for developers.

And what the company realized really early on is that… so our founder, Jeff Lawson, he is a developer himself. Actually, I would say Jeff Lawson is the best developer evangelist at Twilio. A couple of weeks into the job I was complaining about live coding, and we can talk about this later on if you like because it's definitely a contentious topic, but I…

**CHUCK:&nbsp;** Wait, you get to write code?

[Laughter]

**CHUCK:&nbsp;** Sorry, I had to go there.

**GREG:&nbsp;** We get to write it on stage. And that is certainly a contentious topic as well. But yeah, Jeff got up on stage and he live-coded in front of 10,000 people at a conference and just nailed it. And I was like, “Okay, I don't get to talk about that anymore, or complain about it anymore.” But developers are super skeptical of anything that feels like a sales pitch. And they're super skeptical of anything that feels like marketing. And so, what Twilio did is they hired developer evangelists to serve the community. And so, the mission of our team is: inspire and equip developers to change communications forever.

And the idea is that if we are just present in the community, if we just show up at events and we help developers and we're sitting there and we're present when they discover when they can do something that they didn't know that they could do before, they'll remember that. They will remember that we were wearing a Twilio track jacket. We can't bend somebody's arm and say, “Build text messages in to your app.” But if we serve the community and the moment ever comes in their life when they need text messages or phone calls or video or chat, they'll remember us if we've been good to them, if we backed it in an unselfish way to them in the past. So, that's the theory of evangelism. How it looks day to day varies quite a bit. But at a high level it's a mix of speaking at events, it's a mix of sponsoring, attending events like hackathons and whatnot, writing technical content, and yes, even doing quite a bit of code ourselves.

**CHUCK:&nbsp;** So, it sounds like the way that you framed this is that your job is to go out there and help the community. Now obviously since you work for Twilio you want to help the community and help them learn to use Twilio for whatever it is they're doing. So, I'm going to go back to one thing that I've said before and that is that I know several people. They look at evangelists as salespeople.

**GREG:&nbsp;** Yeah.

**CHUCK:&nbsp;** And to a certain degree you are.

**GREG:&nbsp;** Yeah.

**CHUCK:&nbsp;** But at the same time it's not… so, [chuckles] dare I say that I was once a missionary for a church.

**GREG:&nbsp;** Yeah.

**CHUCK:&nbsp;** And our job wasn't to go out there and push people on what we were teaching. Our job was to go out there and meet people and help them. And in a lot of ways, if people wanted to talk to us then we would happily talk to them and help them out. And if people didn't want to talk to us then we just move along and find other people. And so yeah, we were kind of… I hesitate to say selling. We weren't out there collecting money or anything for the church. But at the same time we were presenting our ideas. I think that's a fair representation of what evangelism is. For the people who need the solution, for people who need what it is that you're offering or can enhance what they're doing with what Twilio provides, then you want to be out there and be a resource to those people so that they can as easily as possible benefit from it.

**GREG:&nbsp;** I am so glad you brought that up because I was wondering if I should mention this parallel. Because I know how contentious the topic can be. So, my father is a pastor. And so, I joke that I'm a second generation evangelist. And obviously, I think one of the first things that turn somebody off is the idea of a developer evangelist, is the name. Evangelism by and large does not have positive connotations amongst certainly United States and especially internationally. And there are good reasons for that. Although I will say that at its best, so growing up in the church and still being involved in the church, it's not as visible a form of evangelism. It's not the bullshit television evangelist you see.

**CHUCK:&nbsp;** Right.

**GREG:&nbsp;** And it's not trying to force your beliefs into the legal system and making people feel guilty for not believing the same way you do. But at its best, religious evangelism does seem to take a service-oriented approach, and this idea that our belief compels us to serve the people and serve the communities around us. And when that's done well the community can't help but ask, “Wait, why are you doing this?” And I do find that there are a lot of parallels between the ideal of religious evangelism and the ideal of developer evangelism. And certainly what we try to do is to take more of the service-oriented approach. The etymology of the word evangelist actually means to spread the good news. And so, I do think that it's way easier to be a developer evangelist if you believe that the product that you represent is good news.

And I've been to enough hackathons now where we take someone who's say written just a… only spent a few days writing code in their life or maybe they're a seasoned veteran developer. And they don't know Twilio exists. They go. They create an account. And five lines of code later, literally five/ten minutes later, their phone lights up with a text message or with a phone call. And the look on their face and this uncontrolled expression of joy, it feels like magic. And if you haven't played with Twilio before, I totally understand why you might be skeptical of that. Bu the first experience with Twilio often feels like magic.

And so, for a lot of people, Twilio really is good news. And for the people who need that, the people who want to send say appointment reminders or they want to build a call center or they just want to send SMS notifications or whatever it is, it really is good news. Just a few lines of code, it solves this problem that used to take a ton, a ton of effort or was a near technical impossibility for the average developer. And being able to empower software developers to work with the telecom system has just had a huge impact on people's businesses and also in a lot of technology for good areas.

**CHUCK:&nbsp;** So, I think we kind of talked around some of what I'm going to ask next. But what are the ways that you get the word out about Twilio? You mentioned hack nights and speaking at conferences. Is there more to it than that other than just being a public face and saying, “Look at this cool stuff you can do”?

**GREG:&nbsp;** Yeah. That's a really great question. There are a million different ways that you can do this job. And I think it looks different not only for every evangelism program but also for any given evangelist. So, I think that the makeup of activities for each evangelist on our team probably looks a little different. But generally speaking, it's speaking at conferences. So, we submit a lot of proposals to conferences. And we speak sometimes about Twilio-related things. So, I've been giving a talk at Rails conferences over the last year on two-factor authentication with Authy which is a company that we acquired last year.

We also talk quite a bit [inaudible] non-Twilio related topics. So, sometimes about non-Twilio stuff. So, I give a talk called 'Developers and Depression' just about mental illness in the tech community. There's a guy named Phil Nash on our team who is based in the UK. He's been speaking a lot about Web Workers lately. Folks will talk about APIs. So, sometimes it makes sense to talk about Twilio but truly, if you're just standing up there in a track jacket or just have the Twilio logo by your name and you empower or inspire a developer, they'll remember. You don't have to drive that home. So, we do a lot of speaking. We do a lot of hackathons.

And then we do a lot of technical writing, so a lot of… so, we probably two-ish, I would say one to two blog posts a month. And those all have quite a bit of code in them. Oftentimes those, I think what we've been moving towards as a team is trying to optimize those more for Google because they solve a developer's problem in their time of need. So, one of the posts I wrote a couple of years ago was about Google Calendar API and Ruby on Rails. And so, you have a developer, they're banging their head against the wall. They google this problem, they stumble across this thing that might be about Twilio, that might not, on the Twilio blog. And that also gets the word out.

And then I'd say we've also been playing around with live streaming on Twitch lately. So, we do a lot of, this year we've been doing a lot of live coding on Twitch. We just created a creative channel and that's been a really fun experiment. And then we're actually putting on a conference ourselves. It's in two weeks from today. It's out in San Francisco. It's called SIGNAL. So yeah, a mix I'd just say of speaking, writing, and coding. And then just being present at events as well.

**AIMEE:&nbsp;** How long were you in the industry before you decided to go this route? And do you feel that your skills could potentially get stale and then you lose credibility? How do you keep up to date on things at more than just a very basic level?

**GREG:&nbsp;** That's such a good question and it is the constant top of mind for us.

**AIMEE:&nbsp;** [Chuckles]

**GREG:&nbsp;** So, I started programming when I was six or seven years old on a TRS-80 doing BASIC. So, super simple stuff. And I've just programmed most of my life and then I worked for a software consultancy here in Chicago for seven years before I did this. And I did a mix of, for a couple of years I was a full-time developer and then did a mix of a bunch of different other things. You know, I was thinking about this earlier today. Chuck, I think you were actually there the day that my career changed trajectories towards evangelism. And it was probably the first time that I spoke about developers and depression at MountainWest Ruby I think it was three years ago last month.

**CHUCK:&nbsp;** Yup, I was there.

**GREG:&nbsp;** Yeah. I was just, I remember that. And I had the opportunity at this consulting gig to do a bunch of different stuff over seven years. I was a full-time developer for a while. I did sales for a while. I did a lot of writing. And then I started doing speaking especially around this topic of depression. And I gave this talk and the response was just so cool. I got to meet so many people and have really great conversations with a lot of people. And it felt like I was making a difference. And out of all the things that I had done in the industry over seven years, it was the coding, the writing, and then the speaking but even more specifically than that, the opportunity to help the community that resonated most with me. And so, about a year later I ended up joining the Twilio team.

Certainly though, I do spend less hours in the week coding now than I did before. I still get to write quite a bit of code. And because of the highly technical nature of Twilio, because our product is an API we have to maintain technical credibility. So, the code I write today probably looks a little bit different, definitely looks different than the kind of projects I used to do. So, I will probably spend a lot more time… so first off, I try to spend about 30% of my time writing code these days. We serve often as customer zero for a lot of the products that come out of Twilio. So, we often are playing around with the pre-alpha versions of the products and giving feedback to the team about it. We need to be very familiar with the products so that we can help our customers out in the field. So, I build a lot of stuff on top of Twilio. I also write a lot of technical blog posts.

And then the coolest part about this job is that I get across a bunch of different languages. So, I came into this job being primarily a Ruby developer. And over the last couple of years I've shipped blog posts or written projects in PHP, JavaScript, Ruby, Python. I played around with some Arduino. And then our big push as a team this year is to start doing a lot more with mobile. So, they shipped us all off to a week-long mobile training at Big Nerd Ranch. So, I'm starting to pick up Android. So, I've got a big book on Java sitting at home. So, while I don't spend as much time diving deep on a single codebase, though there are a couple of pretty large projects, relatively large projects, that I've been able to work on, what I think I make up for it is just familiarity with a bunch of different languages. Because when we go to a hackathon, I've literally had hackathons where I've been able to help folks debug across PHP, Python, Ruby, JavaScript, Arduino, Java, all over the course of 24 hours. And it's not to say that I'm proficient in all those languages. But we can certainly play around and recognize the syntax and have an idea as far as how to help folks get through their thing.

So, it's absolutely a trade-off. I think for me, if I were to really just bust my ass, I could probably be a solid B+ developer. But I don't think that that's how I can contribute the most value to the world. I also really like the people aspect of things. I really enjoy speaking. I really love teaching. And I think the overlapping skill set there is what makes for good developer evangelist candidates. Folks who not only love to code, but who also like the teaching and enjoy the people side of things as well and the communicating side of things as well.

**AIMEE:&nbsp;** Being that you work at Twilio, you get to maybe deep-dive into SMPP a little bit and stuff like that, or no?

**GREG:&nbsp;** Yeah, it's actually interesting. We just launched SMPP. So, making that available for folks who are probably, who built out SMS integrations probably pre-Twilio. So, I actually do not work on the Twilio product stack at all. I don't ship code to that. What I do is build a lot of things on top of Twilio. So, I work with a lot of our new products. I've built probably several dozen SMS apps or voice apps over the course of time. But I'm not actually committing code to the actual product in Twilio. We've got engineers who are a lot better than I am working on that and who are doing that full-time.

**CHUCK:&nbsp;** So, I guess my question is what's the most important skill for people to have as an evangelist?

**GREG:&nbsp;** Well, that's a really great question. So, we have four things that we look for when we're hiring folks. The first is technical credibility. And again, I think this is different from program to program, because the nature of Twilio, we call it an invisible product. It's a REST API or at least historically has been. Everyone on our team has worked as a professional developer at some point in their life before. They have code living in production somewhere. They've shipped code to production. So, that has to be first and foremost. If you don't have credibility with developers, you just can't do this job. So first off, it doesn't have to be across a bunch of different languages but the person does need to have gone really deep on one language and have mastery of at least one language. Because often that then translates to picking up other languages.

Second would be patience. We spend a lot of time answering the same one-on-one questions over and over and over again. It's not uncommon you get the same question a dozen times at a hackathon or online. There are a lot of really incredible developers out there who just don't have patience to teach.

The third would be empathy. So understanding, being able to put yourself in the position of a developer, being able to put yourself in the position of learning something new for the first time, understanding that folks aren't necessarily interested in Twilio. They're interested in what they can do with Twilio. They're interested in how it makes their app better, how it makes them more money, or how it makes their lives easier, how it impresses their boss. Understanding how to… just what's going through it. You need to have a lot of empathy in this role.

And then the fourth is hustle. That's the best way that we've figured out to describe it. We work independently a lot. It's not uncommon for me to go days without talking to my manager. Our team is mostly distributed. I'm the only one in Chicago. And we more or less pick the events that we submit to. We more or less pick the events that we sponsor. We almost always pick the content, the topics that we write. You really have to be pretty self-driven to do this job. And so, we often find that a lot of folks on the team have some sort of entrepreneurial background. It doesn't mean they had any kind of… like a lot of us have started failed startups or just side projects. But just people who have taken some sort of initiative. I think a lot of folks probably come into this job with a personal blog where they published a lot of stuff before. I think most developers who end up doing public speaking show some degree of hustle. Because it's typically not your boss pushing you out to do that. You're typically not getting paid to do that as a developer. It's typically something you're doing after hours or even sometimes on your own dime to travel.

So, those are the four things. Technical credibility is first and foremost. And then patience, empathy, and hustle. What we at least look for when we're trying to bring folks in.

**CHUCK:&nbsp;** The other question I have is sort of related to that. And that is if I'm a developer out there at a company and we have decided that we do need the mobile capabilities that are offered by Twilio and we find that part of our team is struggling with Twilio, what's the best way for us as developers to take advantage of an evangelist at the company that we're trying to get help from or trying to use their product?

**GREG:&nbsp;** Yeah, and that's a really great question. And I think there are two things wrapped up in that. One is simply reach out. Most of us are pretty visible on Twitter. I'm @greggyb or [gb@twilio.com](mailto:gb@twilio.com). Email me and if it's not my specialty I'll figure out someone who can help you. Then the second thing is our support team is actually made up of a whole bunch of people who also write code. So, you can always fire off an email to [help@twilio.com](mailto:help@twilio.com). You can copy and paste source code in that. And you will get an answer of corrections. And they are fantastic.

And then the third issue is that our team again spends a lot of time writing technical content. So hopefully, we have done a good job of A, writing documentation. We have a spin-off of the developer evangelism team called the developer education crew and they write our technical documentation and a lot of tutorials. And then we have a lot of blog posts dealing with things. Hopefully we've done a good enough job that in a large number of those situations someone can google the problem they're trying to solve and find the blog post we've written, find a question on Stack Overflow that we've answered, or they can find a tutorial or the documentation is clear enough that they can get up and running. And we started playing a lot more with like I said earlier video this year, too. So hopefully, we'll have a lot more video tutorials out there.

So, that is often a question of how do we scale our efforts so that we're not spending all day long in email. But if you don't find the answer out there [inaudible] that process entirely, either at [help@twilio.com](mailto:help@twilio.com) or drop me an email and we'll figure out how to get you up and running.

**CHUCK:&nbsp;** Do you find that it works sort of the same in other companies that do evangelism or do you not really talk to evangelists from other companies?

**GREG:&nbsp;** Yeah, we definitely see them at a lot of events. You end up standing… seeing a lot of the same speakers on the circuit and at events. I think it definitely looks different at each one. We have the advantage at Twilio of having a developer as a CEO who implicitly believes in the power of evangelism and has a lot of empathy for developers. Where we've seen some other programs struggle before is when they have a non-technical person running the shop. And while it's not impossible to measure it is difficult to measure the output and the results of evangelism. And as a company grows larger sometimes evangelists will struggle to demonstrate with numbers that their program should continue to exist.

And so, sometimes we've seen evangelism programs turn into more of a sales role where evangelists who used to have more free reign now have things like quotas of how many startups did they sign up at incubators. Which, we have no commission. Our performance reviews are not based on numbers. It's just we do our thing. We do measure our activities really for the sake of our own motivation. It's nice to know that you're having an impact. And we want to see if the things that will, at least directionally speaking, work. But it's never like, “Hey, your target was 25 and you only got an 18 and therefore dot-dot-dot.” So, I do think that we're really fortunate at Twilio.

But there are certainly some other great programs out there, programs that are quite similar to ours. But I think there's often a struggle of trying to figure out how do you do this in a way that's serving the community? But also sometimes we're playing… we're often playing the long game. We're not going to see. Spending times at college hackathons where these developers aren't going to have full-time jobs for a couple of years at companies where they're going to be doing a lot of revenue, you're can't really prove that that was worth the money and time that went into sponsorship if you're just looking quarter by quarter. So, I think we're in a pretty good spot there. And there are certainly some other programs out there who are in similar spots. But we've also seen a lot of spots struggle there trying to figure out how to justify their existence, so to speak.

**CHUCK:&nbsp;** Gotcha.

**AIMEE:&nbsp;** So, have you ever been in a situation where potentially, or maybe not you specifically but talking to anyone else who's a developer evangelist, how do you handle cases where maybe you had a security breach or lost someone's data or just a larger scale issue?

**GREG:&nbsp;** Yeah, that's a good question. I'm trying to think if there's anything recent like that for me. I know that before I joined the team there was a billing issue. I think the first and foremost, and there are certainly a lot of smaller screw ups too, right? And I think the strategy is the same for all of those. First and foremost is empathy, empathy and authenticity. Developers just, we know bullshit when we see it. So, you just say, “Hey, we screwed up. And we realized that this has caused you a lot of pain and a lot of frustration. And we're really sorry. Here's what we're going to do to make this right in your specific scenario. And here's what we're going to do to make sure this doesn't happen in the future .”

I think rather it's an individual that has a small problem or it could be like a conference organizer and you forgot to write them back, stuff like that, all the way up to the bigger things. The playbook is the same. You just express empathy and understanding, realize that you have seriously at least inconvenienced this person, perhaps all the way up to caused a pretty serious impact on their business that hopefully you can resolve. But yeah, you first and foremost just admit responsibility and show empathy for the situation they've been in. And then demonstrate that you're going to do what you can do to fix the situation and make sure it never happens again in the future.

**CHUCK:&nbsp;** If a company decides that they want to try having an evangelist team, what would you recommend that they do to get that started?

**GREG:&nbsp;** That's a really good question. I think that you probably want to find someone who's already been serving the community. I think a lot of folks who make good evangelists come into it already doing the job. They were already speaking at conferences. They were already committing to open source. They were already hosting a podcast. But they're also working as a full-time developer. So, I think that quite often the folks who are really good at this were doing it before even if it was unpaid. I think that when a lot of us have, I know at least when I have time off and take a vacation I often will crank out a couple of blog posts on my personal blog. Because these are just the stuff I enjoy doing. And it just got really fortunate that I got a job where I can get paid. So, I think that's often a good indicator if you're looking for your first evangelist, is: are they already doing this? Are they passionate? Because man, it could be a really, really tough job if you're not really into it. There can be a lot of travel. There can be seasons where it's really tough and there's a lot of… burnout is a constant threat in this profession. And so, you really want to find someone who's really into it and not just doing it for a paycheck.

And then the second thing I would do is figure out what metrics you are going to use to figure out if they're doing a good job or not. Understand that it's a very imperfect measurement system. But there are some things you can look at directionally to tell if you're moving the needle or not. And I think it's really good to set those numbers up ahead of time for the sake of both parties. So, you want to feel like… you want your developer evangelist to feel like they're making an impact and not feel like it's just groundhog day where they wake up, they hop in an airplane, they go do a thing, and then they come back and they're just repeating that every single day. It's really nice if they can see some sort of cumulative effect over time. So, I would figure out what those numbers are.

And then I would also just realize that this is going to be a long game. Make sure that you're really into it. And make sure that if you're a startup and cash flow is a concern, you probably don't need evangelists. You probably need salespeople. And if you're going to hire an evangelist, don't treat them like a salesperson. Really make sure that you're investing in them and that you are willing to spend some time and spend some money on this program for long-term results, not just something that's going to pump up the revenue over the next couple of quarters.

Can I ask you all a question?

**CHUCK:&nbsp;** Yeah, go ahead.

**GREG:&nbsp;** When you get out, you guy go to a bunch of different conferences and whatnot. When you see evangelists, what's your impression and what have you seen as far as the evangelists, the evangelism that's worked really well for you versus what hasn't?

**CHUCK:&nbsp;** That's interesting. I've actually been to a hackathon put on by Twilio. I don't remember who the evangelist was. It was here in Salt Lake two years ago with the local JavaScript group. And it was just fun because they led us through a workshop where people texted. So, you'd code something in and then I think it wound up texting or calling the person that was leading the workshop's phone. And then they'd get more information and then you take that information and you do the next step. And you puzzle your way through. I don't remember exactly how it all went but it was something like that. And that was a lot of fun. And I found that a lot of the evangelism really works well when it's hands-on. I've seen evangelists give talks. And sometimes it's something I'm interested in and sometimes it's not. But the workshops I think really are the money for me. It's like, “Oh, I get to do this fun, cool stuff.”

**GREG:&nbsp;** Very cool. What about you, Aimee?

**AIMEE:&nbsp;** I think for me it's really just knowing that whoever the evangelist is that they have some credibility behind them. We do have to remember we love to heads down and code. But we're not going to get paid unless there is someone making some sales.

**GREG:&nbsp;** Right.

**AIMEE:&nbsp;** We won't be able to have our jobs otherwise. So, it's like that delicate balance. But first and foremost having the person who when I talk to them I can talk to them like a developer. I'm not talking to them like a salesperson.

**GREG:&nbsp;** Aimee, I read a bit of your blog. You're a pretty talented writer.

**AIMEE:&nbsp;** [Laughs] I'm not so sure. Don't say that. [Laughs]

**GREG:&nbsp;** [Chuckles]

**AIMEE:&nbsp;** Now I feel like [inaudible] embarrassed.

**GREG:&nbsp;** You typically write more technical content, right?

**AIMEE:&nbsp;** So, I think the last post that I wrote was something on Nginx and Angular.

**GREG:&nbsp;** Yeah.

**AIMEE:&nbsp;** I don't know. I think that was at the end of last year. So, I don't write a ton. It's something that I would love to do more. But the podcast is [chuckles] probably what I do a lot more of. But yeah, I think like I said, just having somebody who is continually trying to just become a better developer even though you do kind of have to straddle that line.

**GREG:&nbsp;** Yeah. That's certainly a challenge. If you're not really intentional about how you structure your day and how you structure your weeks and months it's super easy to let the more urgent stuff crowd out… because if you're going to really code and get better at coding you need long blocks of dedicated time. And you typically don't have long blocks of dedicated time to do that unless you create that time and block it off on your calendar. And so, I know that several of us do on the team just block off our mornings. So, my calendar typically will have from nine until noon every day just, it's a recurring event that just says production. And that is either producing code or it's producing blog posts. Or often those two are intertwined because I'm producing code for a blog post or I write some code and I write a blog post around it or something. But I do think it's super, super important if you're doing this job that you create time on your calendar where you can just dig into the code and spend lots of time. Because you're absolutely right. If you lose the credibility you can't do the job. And I think the only way to maintain that credibility is to be very intentional about it.

**AIMEE:&nbsp;** Yup. And I'll say too, I feel like… so, most of the evangelists I've ever met, they're pretty friendly. I think it definitely takes a certain individual because there are a lot of developers who, they can only do so much social interaction then get really tired. [Laughs]

**GREG:&nbsp;** Yeah. No, for sure.

**AIMEE:&nbsp;** So, you have to have that balance where you still enjoy programming but also are okay being out in front of people for long periods of time and traveling and all that, where it doesn't wear you down where you become grumpy. [Chuckles]

**GREG:&nbsp;** Oh, but I definitely get grumpy.

[Laughter]

**GREG:&nbsp;** I [upset] everyone on my team because I'm grumpy sometimes. And that's a really good point though. So, the very first evangelist I ever met, it was a few years ago and I remember talking to him. And I was like, “Man, I think I would really enjoy your job. Unfortunately I also really enjoy being married and I'm not sure I could do both at the same time.” Because he traveled a hundred thousand miles a year. I don't even think he had an apartment in the town he called home. And when you meet a lot of evangelists, that is the story. They fly around state to state, or internationally even a lot, giving talks everywhere, racking up tons of frequent flier miles, spending a ton of time on the road.

And part of the industry thought is, I think this is changing a little bit, but often it was just like, “Hey, evangelists are only going to do this job for 18 months.” You're going to come on, you're going to do this job, you're going to get burned out, and you're going to do your next thing. But you will build up this platform and will have gotten your name out there and stuff. And so, it's going to be good for you. But you're only going to last 18 months. And we just fundamentally believe that that is the absolutely wrong approach. And that A, you can do this job sustainably. I do believe that for me, I have the best possible job I could have at this point in my life.

But to your point, Aimee I do think that it is not for everyone but for the people who is probably for more people than they would necessarily think at first glance. Which is part of the reason why I really appreciate you having me here because I do think this is an incredible job. And I also know that there's a lot of confusion about the job and whatnot. So, I really appreciate the opportunity to chat about it. Because whether someone's working for Twilio or elsewhere, it's just… if you enjoy speaking, you enjoy writing, you enjoy coding, it's a fantastic gig. But we do want to structure the program in such a way that you can do this for a long time.

So, we actually travel quite a bit less than most programs. I think I flew about 30,000 miles for work last year, which is a lot more than the average developer but it's a lot less than the typical developer evangelist and it's a lot less than say if you were working at a hundred percent consulting job or something. I think in my worst month I was away for 12, 13 nights in a week. Or I'm sorry, in a month. 12, 13 nights in a week would be pretty bad. But I have an 18-month old daughter. I have a wife. I really want to… it takes a little out of all of us whenever I'm gone. And the team respects that and the team fundamentally believes that a developer evangelist is going to be a lot better at their job on the second and third year than they are on the first year. You just learn a lot. You build better relationships. You learn which events make more sense to invest your time and energy into. You'll give better talks. You'll be a better developer.

And it just doesn't make any sense at all, especially given how hard it is to find people to do this job, to put them in there for 18 months and then send them on their way and just treat them like a racehorse that you can just run really hard and then put down. And so, it's something we believe very passionately in. Our goal every year is to have a hundred percent retention on our team. And we actually hit that last year and had nobody leave. And I really think our team is a lot better for it. But it absolutely can be tough at times. The travel can be hard at times and there are seasons of the job where it's super, super busy. Fortunately there are seasons.

Typically we have our hustling season in the spring and fall where there's a lot of events. We're going really hard. We're traveling more. And then I think I went the second half of December, January, and February, so for say 10, 12 weeks almost, I didn't get on a plane except for I think once for work. So, it's a very seasonal gig where what you're doing each day looks a little different depending on the week or month of the year. And so, when you are going really hard and you're getting pretty rundown, it's good because there's typically a light at the end of the tunnel. And you'll say, “Okay, just a couple more weeks and we're going to get to rest.”

And Twilio has unlimited PTO. There's a lot of debate unlimited PTO in the industry. But at least on our team, I think most folks on our team take about six weeks off over the course of the year. So, they're absolutely are some 50, 60-hour work weeks. There are absolutely some stretches where it feels like you're not home very often. And then there are… we'll all take long vacations a couple of times a year. And so, I just really appreciate that aspect of the job.

And I guess to your question earlier Chuck, something that I would encourage someone who's looking to start up one of these programs to do is be super, super flexible with your person. If they… I've heard of evangelists before who have to go work a meetup and then be back in the office at 8am the next day or spend all weekend at a hackathon and show up on Monday. It is just insane. And so, trust them to do the job and give them a lot of flexibility over their schedule to do it in the best way that they know how.

**CHUCK:&nbsp;** Makes sense to me.

**GREG:&nbsp;** For what it's worth, I feel like Chuck, I would consider you very much to be an evangelist in what you do. And I know you don't necessarily have a specific product but you have just been… done so much good for the community through your podcasts. And the amount of content that you put out and the consistency with which you do it is just super, super incredible. I really think that you provide a really great service to the community. I think there's a lot of people who are probably employed or are better at their jobs, I think that's probably an understatement, because of the work that you put in. And yeah, it's really, really cool to watch. I started up a Twilio podcast earlier this year and have not had nearly the consistency that you have. And you're definitely a bit of an inspiration when I see this 240-something number that this episode is. And this is one of 28 podcasts that you put out. It's certainly convicting as we start thinking a lot more about how do we scale our program?

**CHUCK:&nbsp;** Well thanks. I appreciate that. And it's interesting because in some ways I guess there are parallels. Yes, I don't have a product that I am pushing toward. If I had any, it's the remote conferences. But it's more of the same as far as putting stuff out there that helps people out.

**GREG:&nbsp;** Yeah.

**CHUCK:&nbsp;** But I had a conversation at MicroConf which was the beginning of April this year. It's 2016 if you're listening in the future. But anyway, we were talking about team organization because that was something that I had been struggling with at the time. And he kept bringing up, and that way you can get the stuff done that you are committed to doing.

**GREG:&nbsp;** Mm.

**CHUCK:&nbsp;** And I just, I was like, well finally it was like, “I don't know what my ultimate purpose is. I don't have a why.” And he says “You do. You just don't know what it is.”

**GREG:&nbsp;** Interesting.

**CHUCK:&nbsp;** And so, I thought about it and I thought about it for probably about a week because it really bothered me that I didn't have a why. And it was like, “Well, I really like talking to everybody. And it's fun.” But what was the why? And I realized that the why was helping people out and making people's lives better. And by understanding that and realizing that that's why I do the podcasts and that's why I do the remote conferences and that's why I do a lot of the other things that I do, I've come to really understand that yeah to that extent I am an evangelist. I'm just not an evangelist for a particular product or a particular library or set of technologies. Instead I'm an evangelist for general understanding across the community and specifically of things that I think will benefit the people that listen to the show.

**GREG:&nbsp;** Great. You are very much spreading the good news. And the good news is not any one particular message in your case. But you are bringing on people who have great things to say about all of these, throughout all these different communities. And you're giving them a voice. You are taking their good news and spreading it out to the community that you have. And you can tell that you do this from an orientation of service. You can tell that you love serving the community. And that's really your motivation there. And it is very cool to see.

**CHUCK:&nbsp;** Yeah.

**GREG:&nbsp;** Hey Aimee, can I ask you a question?

**AIMEE:&nbsp;** Yes.

**GREG:&nbsp;** As skewed as the developer population is towards men, the developer evangelism program or population is even more skewed towards being men. And I think there are probably a number of reasons for that. But I'm interested in your take on that. Given that you enjoy writing and given that you enjoy coding and given that you enjoy being a public figure, is it a role that you would ever consider? And how does being a public female figure in the industry affect you and do you have concerns around that?

**AIMEE:&nbsp;** Hmm. [Laughs] That's a loaded question. So, to answer the one question it is something that I've considered because I feel like you. It's something that I would really enjoy. Even at my last job there were conversations about it. But because I'm still newer and stuff, I just really wanted to spend more time learning before I went into a role like that.

But as far as being a woman, I'm probably not going to be able to pronounce her name correctly, but I think she was a developer evangelist for Mozilla. I would have to google her name, but anyways she… I've had a few conversations with this woman and I feel like she has a really good insight into it. Her view is when she goes out to speak or do any sort of events in the community she just wants to be known for her content, not by the fact that she is a woman. So, she just always focuses on that. And I think that is also really important, because I feel like if you don't focus on that, unfortunately because the industry is so male-dominated that unless you have some strong technical skills the only way that your voice is going to be heard is to be loud. [Laughs] And for some women that's okay. But I feel like for others it's not something that comes naturally usually. So, I don't know. Those are my thoughts around that. [Chuckles]

**GREG:&nbsp;** Well, I appreciate you answering the question. My apologies for the difficult question. I do…

**AIMEE:&nbsp;** Oh, it's [inaudible]. [Chuckles]

**GREG:&nbsp;** Yeah. I would encourage… you went to a coding school, right?

**AIMEE:&nbsp;** I did.

**GREG:&nbsp;** Was it Nashville?

**AIMEE:&nbsp;** It was the Nashville Software School and I was the only female in that cohort.

**GREG:&nbsp;** Oh, okay then.

**AIMEE:&nbsp;** Or the only female… there were a couple that started but they didn't finish. So [chuckles]

**GREG:&nbsp;** Okay. Well, for what it's worth, two things. One, I think your inclination to get more developer experience is just spot on.

**AIMEE:&nbsp;** Yeah.

**GREG:&nbsp;** And we've had people interview with our team in the past and then drop out of the interview process because they wanted to spend a couple more years being a hardcore, heads down engineer. And…

**AIMEE:&nbsp;** Yeah.

**GREG:&nbsp;** We've never faulted anyone for that. We're always like, “Hey, good for you. Come back if you ever want to chat about it again.” You can never have too much credibility with developers. But with that said, I do feel that not necessarily right away, but the graduates from the code schools like Dev Bootcamps and whatnot are really interesting candidates for evangelism programs. Because I do feel like most of them need to go spend a couple of years. We've never hired someone directly out of that program as their first gig straight into an evangelist role. I do think you need to work as an engineer for a couple of years before you do it. But most people who come into those code schools come in with a pretty rich career history or at least life experiences prior to going into that school. And a lot of them come in, come from worlds like I've seen.

I do a lot with Dev Bootcamp here in Chicago and I see a lot of teachers come through there. I've seen writers come through. I've seen… actually, I have a friend who is a former pastor who went through the program. And I think because you do need to have a bit more balanced skill set and more life experiences in order to be super effective at this role, I think a lot of people who go through the code school stuff and have these interests other than just pure coding, once they get a couple of years of engineering experience under the belt, often will make super interesting evangelism candidates.

**AIMEE:&nbsp;** Yeah, I think so.

**GREG:&nbsp;** I really enjoyed working with the code schools over the last couple of years. It's been just… if you figure what is required in order to put your life on hold to go to one of those things and shell out the cash for it and none of those are easy programs. They require incredible commitment and just to pivot so hard on your career. Yeah, it's just been really rewarding working with them. It's been one of the fun parts of this gig. I can then just go and mentor at these things and it's part of my job. I get paid to do that. And there are a lot of folks who… a lot of developers deserve a lot more credit for that who, they put in their 40, 50 hours and then go to these code schools and mentor. They go to the local high school and mentor. And whatever it is, however they're helping out the community.

One of the best parts about this gig is the fact that I get paid to go help. And it's just the incredible amount of warm and fuzzy feelings that come out of this thing. We get emails all the time. Or there's an email of someone who saw my talk on depression and they decided to set up an appointment with a therapist or something. It's like, that was super, super cool to be able to have that impact. But I flew there on Twilio's dollar. I stayed in a hotel on Twilio's dollar. I spoke during the work week and when I got back I didn't have a backlog of work to do because I was actually doing my job. And same with at the Dev Bootcamps and whatnot.

And so, that's why, again just to reiterate, for the folks who have any kind of inclination to do this gig I would love to chat about it. Because I do totally understand the skepticism towards it. It has a weird title and the line's not super clear. And the job's not super well-defined. But for the right person and in the right program it can be so incredibly rewarding.

**CHUCK:&nbsp;** Awesome. I think that's a really positive note to wrap up on.

**GREG:&nbsp;** Sure.

**CHUCK:&nbsp;** So, let's go ahead and do some picks. Aimee, do you have some picks for us?

**AIMEE:&nbsp;** I do. So the first one, this was actually recommended to me by somebody. And there's a book as well but I've just watched the TED talk. But it's called 'The Power of Vulnerability'. So, somebody sent that over to me yesterday after just a discussion about how we balance. Like, I'm married. I don't have children but this person is married with children and just as developers going to conferences and stuff, we are a lot of times surrounded by people who are single. They don't have families, really. And just how difficult it can be to balance this industry with having a family. So, it doesn't really specifically get into that point. But I think it is very much related to that point. Anyway, so the book looks really good. And once I read it, I will report back on that.

The other one is programming related and I heard this on Ruby Rogues actually. But I think Avdi picked it but it's called 'The Fallacy of ReUse'. And I just thought that the post had some really, really interesting points that I hadn't heard made before. And it got me thinking. So, that is it for me.

**CHUCK:&nbsp;** Alright. I'm going to go ahead and throw out a quick pick here. That pick is Calendly. I don't know if anyone's used Calendly.com.

**GREG:&nbsp;** I use it and love it.

**CHUCK:&nbsp;** So, I'm actually working on getting things set up so that we can do episode scheduling with Calendly instead of Mandy trying to figure out which Tuesday people can talk on. And yeah, I'm really excited about some of the possibilities with just being able to automate some of these really simple things. And Calendly is a part of that.

I've also been… I switched everything over to WordPress. So, if you run into any crazy stuff on DevChat.tv that's not working or not working right, ping me and let me know. And we'll get those fixed. But I've been using Gravity Forms to allow people to suggest other guests. And that's been working out really nicely. What happens is the suggestion goes into Gravity Forms which is a plugin for WordPress. And then Gravity Forms publishes a feed that Zapier can pick up. And then Zapier picks up the feed, or maybe it's the other way around. I think I get the feed URL from Zapier. But anyway, so it hits Zapier's API and then Zapier goes ahead and sends me an email [chuckles] and puts it into a Trello board where we can keep track of our guests. So, we can see the progression as things move through the system. So, that's super exciting and really nice just having a way to keep track of what's coming up. So, as I get that fleshed out and get that visibility on it and I've been inviting the other hosts to join in on that and have that visibility, it's been really awesome. So, I'm really, really liking it.

I'm also going to pick Trello. I have a 90-day sprint that I started. It was something that my mastermind group is doing. So, in 90 days we're all trying to accomplish something. And for me it's the automation and documentation on how we do everything for the podcast and the conferences at DevChat.tv. And so, I set that up and I invited all of the members of my mastermind to have a look at it. And I'm bringing Mandy and then I'm bringing a few other people in so that they can help me get all of that stuff done. And anyway, it's just really awesome because it makes it really easy to manage that list of stuff that has to get done and then watch as it progresses through.

I also use it for my personal to-do list. So, I have to-do and then I have in flight, delegated. So, I could keep track of, “Okay, this has been delegated to Mandy. This has been delegated to somebody else. This has been delegated to a developer.” And I know, “Okay, I need to follow up on this and make sure that I know where things are on that stuff.” And that way nothing gets dropped because that was always my problem running everything with those shows. With five shows and a conference every month it's just really hard to keep track of everything. So, if it's on my list as delegated then I know, “Okay, I haven't heard anything about this, this week,” so then I can follow up. And I can talk to Mandy or Federico who's the developer that I usually have work on stuff for me or whatever.

One last or two last tools that I've been using for this is Slack. I've really gotten into using Slack lately. And it's nice because I can pull everybody into the same channel and then they can communicate. And we've been using Zoom, Zoom.us, to do our team meetings. We've been doing that every Monday. And that's also been really helpful because we can check in. we can see where things are at. We can make sure everybody understands what's what. I actually spent a little extra time on Zoom yesterday after the meeting trying to debug stuff on the conferences site. And it's just a really convenient tool for sharing screens and communicating and all that stuff.

So anyway, I guess that's a really long-winded pick. But those are the tool that I've been using lately. Greg, what are your picks?

**GREG:&nbsp;** Well, I want to plus one Calendly and Trello. For Calendly, it's super nice for everyone to hop on a phone call when I just shoot the Calendly.com/Baugues/phone or whatever. And they just add time right to my calendar. It saves so many of those threads back and forth. Like, “How's Tuesday at two?” “No, that doesn't work for me” And Trello, we have six or seven. Our whole program is basically run off of Trello. So, it's a great program there.

Another tool I use a lot is called Talky.io. So, it's like Skype in the browser. So, you go to Talky.io, in my case, well you don't have to reserve a URL or anything. Just go to Talky.io and I do '/Baugues' but you can make up any URL. And anyone who meets you at that URL is dropped into a video chat. So, you don't have to trade usernames. You don't have to install Skype. You don't have to have a Gmail account. Just go to this URL. You're dropped into a video chat together. It's fantastic for ad-hoc conferences. So, when I'm setting up meetings with people I shoot them my calendar link. They put time on them. I'm like, “Cool. Meet me at Talky.io/Baugues.” Then we hop on there and we talk. And it's just been fantastic.

**CHUCK:&nbsp;** Does it record?

**GREG:&nbsp;** It does not record. You cannot use it for this.

**CHUCK:&nbsp;** Okay.

**GREG:&nbsp;** Yeah. So, it uses WebRTC. And I'm not sure how well it scales past say four or five participants. Because WebRTC doesn't typically… WebRTC is all direct connect. Anyway, whole different topic. But yeah, it's fantastic for just the one-on-one talks.

I would also say the probably a bit too… I don't know. In two weeks we're putting on a conference. May 24<sup>th</sup> and 25<sup>th</sup>. By the time you're listening to this it will probably be done. But it's called SIGNAL. We have over a hundred speakers. The videos will be online shortly after the conference. It's going to be awesome. We've been working on it a ton. And so, check that out.

I listen to the Tim Ferriss podcast a lot. And it's just been great. In particular I just listened to the Mike Rowe from Dirty Jobs episode and then also the Jocko Willink. He's the commander of the most decorated special operations unit of the Iraq war. And just the things he says about leadership is just this glimpse into a totally different world than what I as a developer am accustomed to.

And then finally the TV show Billions. I just watched, I mentioned it on Ruby Rogues too, and plowed through all 12 episodes in less than two weeks. And it's about, I don't know, just check it out. You can find it on Amazon Prime. It's pretty great though.

**CHUCK:&nbsp;** Alright. Well Greg, how do people find you if they want to connect?

**GREG:** &nbsp; I am @greggyb on the Twitters. G-R-E-G-G-Y-B. And I'm [gb@twilio.com](mailto:gb@twilio.com) if you'd like to drop me an email.

**CHUCK:&nbsp;** Alright. And with that, we'll go ahead and wrap up and we'll catch everyone next week.

**_[Bandwidth for this segment is provided by CacheFly, the world’s fastest CDN. Deliver your content fast with CacheFly. Visit CacheFly.com to learn more.]_**

**_[Do you wish you could be part of the discussion on JavaScript Jabber? Do you have a burning question for one of our guests? Now you can join the action at our membership forum. You can sign up at JavaScriptJabber.com/Jabber and there you can join discussions with the regular panelists and our guests.]_**

**_[End of podcast]_**
