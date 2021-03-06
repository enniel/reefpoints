---
layout: post
title: "Goodbye Heroku"
author: 'Brian Cardarella'
twitter: 'bcardarella'
github: 'bcardarella'
social: true
summary: 'Done with them'
published: true
tags: opinion
---

I've been a Heroku user since the beginning. And I understand they have
had their ups and downs but over the past 2 years the service has been
degrading and today was the last straw for me. Allow me to elaborate.

## Downtime

Today Heroku had a "Scheduled Maintenance at 2pm EST". First of all,
this is just stupid. Don't schedule a maintenance period at 2pm EST for
**anything**. That period of time has to be one of the most heavily
trafficked timeslots on the web. Its an hour after everyone on the East
Coast has come back from lunch. It is an hour before lunch on the West
Coast. This, to me, demonstrates a lack of judgement on Heroku's part. I
know the counter-argument is going to be "we've done plenty of other
scheduled maintenances at 2pm EST without incident". My reply is that
this counter-argument is *bullshit*. Just because you got away without
problems previously doesn't mean they won't happen in the future. Things
go wrong, people screw up. When Heroku has control over when those
screwups occur and they choose to push that risk at 2pm EST that is a
problem.

## Reporting of Downtime

I am convinced their Status team just sits on Twitter all day and waits
for enough people to bitch and complain that Heroku is down before they
update the status page. I don't care what data they provide to the
contrary. Why is the updated status page important? When our customers
email us during our vacation pissed off that we are not around and we
have *nothing* to show to them to prove that this is Heroku's fault and
not ours, to me that status page being updated immediately **before**
our customers discover on their own is very important.

## Price

It has been heavily reported that AWS has cut their pricing quite a bit
over the past few years. Yet, how many times has Heroku reduced its
price? (Heroku resells AWS) To my knowledge **zero**. So everytime Amazon
reduces EC2 pricing Heroku just pockets the difference and gives a "fuck
you very much!" to all of its customers.

## Fixes for All

The major downside to hosted devops is that when something goes wrong
that affects everyone you usually have to wait until they make the fix
for **everyone** before your app comes back up. What should probably be
a 5 minute downtime *at most* turns into a 30 minute downtime **at least**.

## Buildpacks

Buildpacks are just terrible.

## Conclusion

I get that I'm ranting and I'm pretty pissed off. But mistakes like
today's are completely avoidable yet Heroku chose to expose everyone to
this increased risk for no good reason that I can see.

We will no longer be starting any new customers on Heroku. And we will
recommend to our current customers to move off of Heroku. We're big fans
of Digital Ocean so we're likely to land there as our preferred hosting
service.
