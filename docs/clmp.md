---
title: Canadian, Local, List Free, Proportionality. CLMP.
description: The details of a MMP system designed by me for Canada
hide: 
  - navigation
---

## Introduction

I have spent quite some time in my life, shouting at anyone who would care to listen about the deficiencies in the "Winner Take All" First past the post electoral system Canada uses at all levels of governance.

Throughout that time I have heard a lot of concerns about how proportional systems operate. Some of these are myths, but others are not. I truly believe that many if not all of the actual concerns can be addressed through designing a proportional system that meets Canadian needs and desires.

So, permit me to introduce the CLMP system which stands for...

* Canadian
* Local, List Free
* Mixed Member
* Proportional

Let's go over the basic features one by one before delving into the mechanical details.

## Basic Features

### Proportional

I'm not going to spend time defending this, I'm just going to repeat a classic quote on democracy that's very hard to argue against:

> “In a democratic government the right of decision belongs to the majority, but the right of representation belongs to all.”

The fact is that proportional systems are the only ones that can fulfill both of these core principles. Winner take all systems routinely violate the first and almost always fail to provide the second.

### Regional and List free.

Canadian political culture, for some very good reasons, places a large emphasis on democratic representation that is tied to a geographic locality. For similar reasons there is also a suspicion of politicians who do not represent a region.

Because of this a very common mechanism of achieving proportionality, choosing representatives from a list prepared by a party, seems to be a non starter. Thankfully there are ways to design a proportional system that does not sacrifice regionality or require a list. CLMP is one of these

### Two Votes, one for candidate and one for party

The idea of being able to vote for a local candidate without also supporting their political party and vice-versa is a popular one. It also manages to increase voter choice and flexibility significantly with only a minimal level of added complexity.

### Mixed Member system

CLMP is a Mixed Member Proportional (MMP for short) system. These systems retain the original single winner take all seats and add proportional seats that compensate parties that are underrepresented in the winner take all part of the results. It's used very successfully in Germany and New Zealand as well as in Scotland and Wales.

The common complaint of most MMP systems is that the additional proportional seats are filled by a list that is prepared by a party. CLMP is a variation that does not have this mechanism. CLMP also ensures that candidates elected to the proportional seats are tied very closely to a geographic region.

## How does it work?

### The current system remains

As in most MMP systems, CLMP contains within it the winner take all contests and seats. Under CLMP these will work in exactly the same way that our current system works. The quick summary is that the country is split into different voting districts (also known as ridings), candidates run in these districts/ridings, and the candidate who gets a plurality of votes (i.e. more votes than anyone else) gets elected to the seat.

While there is no necessity for a political party in the system, in practice they form and have a very large influence on the election. In CLMP these will be known as *riding seats* or *district seats*.

### Seats are grouped by region and each region gets seats

Seats will be grouped by region, a city like Toronto for example would be a region of its own. At the minimum each province or territory would be their own region. Each region would get regional seats. The more regional seats there are, the more proportional the system would be. I would suggest that at least 30% of the seats overall should be proportional. These seats will be known as *regional seats*

### Ballot design

Elections would be run at the district/riding level. Voters will get a candidate ballot and a party ballot. The candidate ballot would work the same as currently with the names of the candidates listed along with their party (with candidates with no party being listed as Independent). The party ballot would contain the name of each party *that is running in the riding*. This will incentivize parties to run as many district/riding candidates as possible otherwise they would not be able to get party votes from that riding.

Voters would be able to fill out one or both of these ballots though they would be encouraged to fill out both.

### Vote counting

* First the riding/district contests will be counted and resolved as previously.
* Parties that do not receive 5% of the vote nationwide will be removed from consideration for the regional seats. This is a pretty typical threshold but 4% or 6% work as well.
* A calculation will determine how many regional seats the remaining parties need to be assigned to achieve proportionality, or at least get close. Calculation details are in the [calculation](#calculations) section. Calculation can be done at the national level or the provincial level.
    * The system would work however if the regional seat calculation happened at a lower level at the expense of some more calculations required and some loss of proportionality.
* If the discrepancy between votes received and seats won at the riding/district level is so extreme that the number of seats required by parties to compensate is more than the number of regional seats available then the number of seats to be assigned will be prorated down to fit.
* All that is left is to assign candidates to these regional seats

### Assigning the candidates by popularity

Instead of choosing the candidates to go on the regional seats from a list, they are instead chosen from the riding/district candidates that did not get elected to the riding/district seat.

These candidates will be assigned a regional seat if:

* They ran for parties that were assigned regional seats.
* They did not get elected to a riding/district seat.

This will be done in order of candidates that won the highest proportion of the vote in their riding/district contest but did not get elected and are from parties that have earned regional seats. I refer to them as the Most Popular Remaining Candidates or MPRCs.

So for example let's say a candidate wins 46% of the vote in a riding/district in Newfoundland but does not get elected. As this candidate has the highest proportion of the vote of all the candidates that did not get elected in the riding/district contest they will be the first to be assigned a seat in the Newfoundland region should their party need seats to achieve proportionality.

The steps will be

* Order all MPRCs by their proportion of the vote in their riding/district contest with the highest on top. Only candidates from parties that have earned regional seats are on the list.
* Assign the highest MPRC to the region their riding/district is in.
* Continue assigning MPRCs to regional seats in this order after removing any that are in parties that no longer need regional seats or are from regions that have all their seats assigned.
* Should a region end up without a regional candidate as all regional MPRCs are in parties that don't need any more seats then the seats will be filled regardless of party.

## Conclusion

There is no perfect system and CLMP is no exception. It foregoes the benefits that a party list can provide (such as guaranteeing representation of women and minorities), it prioritizes regionality over proportionality in some scenarios so is not the most proportional. Just like any system it can lead to odd outcomes and be gamed by clever party strategies.

However the system combines good proportionality with high regionality and does so without the need for party lists or for voters to rank all the candidates on a ballot.

It allows voters to split their vote and choose a strong local candidate regardless of party and still express their preference for a different party leader or policies.

It incentivizes parties to run strong local candidates in as many ridings/districts as possible.

It incentivizes candidates to get as many riding/district votes as possible as the only guarantee they have of getting elected is to win the riding/district contest and then failing that, to be as high on the MPRC order as possible.

This almost certainly won't go anywhere, but in order to achieve progress, we have to first speak it. And that is what I am doing here.

And as always. Free Palestine, Free Sudan, Free Congo, Free Kashmir. God free us all.

## Appendix

### Calculations

#### How many regional seats does each party get?

The calculation is carried out like so:

* First determine the Proportional Eligible Vote Percent (PEVP).
    * This is the sum of the percentage of votes received by parties that meet the threshold.
    * For example if one party doesn't meet the threshold and gets 2% of the vote and independents get 6% the PEVP will be 92%
* Next determine the Proportional Eligible Seats (PES).
    * These are the seats in the full parliament including both regional and riding/district seats that have not already been taken up by candidates that are either independent or from parties that did not meet the threshold
    * Total Number of seats - number of candidates elected that are not in parties that met the threshold.
    * For example if total number of seats is 455 and 2 candidates were elected that are not in parties that met the threshold the PES would be 453
* For each party that meets the threshold determine how many seats a party should have in the full parliament by using the following formula
    * (Vote share of Party/PEVP)*PES
    * Parties that don't meet the threshold keep their riding/district seats but don't get any more.
* Subtract the number of seats that a party won in the riding/district level from the number they should have overall according to the above formula and round it as normal. This number cannot be less than zero
    * This is the number of regional seats the party is assigned
    * Should the total number of regional seats needed exceed the number of regional seats available as can happen with extreme levels of distortion at the riding/district level, the number of seats a party is assigned is to be prorated as needed.
    * For example if 150 seats are needed with party A receiving 100 and party B receiving 50, but only 100 regional seats are available, then party A would receive 67 seats and party B would receive 33.

### Simulation

* [Federal 2021 simulation including candidate assignment](clmp_2021.md)
* [Federal 2025 (Preliminary) including provincial level vote calculation](clmp_2025.md)
