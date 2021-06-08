# Project #62: Anti-Crypto Coin Public Ledge Accounting
Build a simple public ledger system to support flows of "karma" to contributors in a graph of innovations

# Idea

This idea is based on "Innovation Bricks" as conceived by Bodo Hoeden of [Dev4x](https://www.dev4x.com/).


What if we build a simple system, perhaps illustrated with a little Javascript power web page, like this:

1. Within Innovation Brick A, some mechanism, perhaps democratic, perhaps dictatorial, distributes A-coins to contributors. At any point in time, there is a list of people who public contributed value and each person is publicly stated to hold x A-coins.
1. Suppose Brick B builds on Brick A. A dictator or democracy in Brick B can assign B-coins to its contributors, but can also give coins B-coins to Brick A.
Now this goes on till we have 10 bricks, perhaps in a tree or even something with a cycle! But a Directed Acyclic Graph is probably simpler than dealing with cycles.
1. Now someone wants to give real money to the network in appreciation and to motivate further work. Let us suppose that they only see Brick G, so they give $1,000 to Brick G, and they do so publicly.
1. Now, G-coin is a "share" of brick G that is fungible; every G-coin is as good as every other G-coin. So the $1,000 is to distributed to the coin G-coin holders. But Brick F may be a G-coin holder because G was built on F; so Brick F gets a share---let's say it comes out to $200.
1. Now $200 is distributed to the F-coin holders, but Brick E may hold some F-coins, so they get some money.
1. Now, over time a contributor to Brick A may get a small amount of money. It might not be much; unless, of core, "A" is an essential innovation which is used by 100s of Bricks. In that case an A-coin holder will get 100s of small inputs, so an A-coin may be worth quite a bit.

Now, this could be done with something other than money. For example, someone could give 100 "karma points" or "likes" or "claps" to Brick G. Some of these will also accrue to Brick A by the same mechanism.

If I contribute to Brick A, over time it will be a public value how may "claps" or have accrued. I can put that on my LinkedIn profile, for example.

All of this can be done with no crypto and almost no software. But it does not support anonymity. I think crooks and weirdos like the idea of anonymously holding something they can cash in at a time of their choosing. But this would all be completely public.
