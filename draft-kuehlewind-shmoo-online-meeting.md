---
title: Guidelines for the Organization of Fully Online Meetings
abbrev: Organization Online Meetings
docname: draft-kuehlewind-shmoo-online-meeting-latest
date:
category: info

ipr: trust200902
keyword: Internet-Draft

stand_alone: yes
pi: [sortrefs, symrefs]

author:
  -
    ins: M. Kuehlewind
    name: Mirja Kuehlewind
    org: Ericsson
    email: mirja.kuehlewind@ericsson.com
  -
    ins: M. Duke
    name: Martin Duke
    org: F5 Networks, Inc.
    email: martin.h.duke@gmail.com


normative:
  RFC8719:


informative:



--- abstract

This document provides guidelines for the planning and organization of fully online meetings, regarding
the number, length, and composition of sessions on the meeting agenda. These guidelines are based
on the experience after the COVID-19 pandemic in 2020.

--- middle

# Introduction

In 2020, the COVID-19 pandemic forced the IETF to move all its plenary meetings to online-only events.
This document mainly records the experience gained by holding all three plenary meetings in 2020 fully online  
and noting down the guidelines that have been followed since. The aim of this document is to determine rough
consensus of these guidelines in the sense that the most participants are sufficiently satisfied 
with the current organization of fully online events. These guidelines, however, document only one option
of running fully online meetings. But as the IETF has done for in-person meetings, changes to the organization
of the meetings and the meeting agenda should be experimented with in the process of establishing future meeting guidelines. 

# Some History

When the WHO declared a world-wide pandemic in March 2020, the IETF had to quickly cancel its plenary meeting
and organize an online replacement instead (within less than two weeks). At that point, for this
first online-only meeting, the agenda was reduced to a set of sessions that benefits most from cross-area
participation, like BoFs, first-time meetings of a new working groups, or dispatch sessions, as well as the 
administrative plenary in order to organize the official hand-over procedures that occur at the March meeting. 

With that reduced
agenda, it was possible to organize the meeting within roughly 2 sessions (about 4 hours) a day and a maximum of two
parallel tracks. This was possible as all working group meetings were instead moved to interims which were then distributed over
the coming six weeks. However, this was often perceived as increased load over a longer time. But at that point of
time there was not necessarily an expectation that the situation would continue as long as it did.

For the following meetings in 2020, the online schedule was retained in a fashion similar to an in-person
meeting (1-2 hour slots and 8-9 parallel tracks as described below), however, still with a reduced total length
of initially 5 hours a day and then 6 hours with longer breaks. As with in per-person meetings, 
the total number of sessions depends on the number of 
requested sessions by working and research group chairs, which were encouraged to request rather shorter and less slots.
However, this in some cases also led to overcrowded agendas and sessions going over time (which
is often also observed at in-person meetings). In general, the total number and hours of interim meetings has probably
also increased in 2020,
potentially indicating a change in the way people work as well as increased comfort participating in online meetings in general.
More interim meetings are sometimes also perceived as increased load but may also help to make more continuous 
progress. This discussion is on-going and not in scope for this document.

All fully online meetings in 2020 have followed the time zone of the planned in-person meeting
location, but starting roughly around noon instead. Some flexibility with the start time to be "around"
noon has been used to mitigate the worse
possible time slots, even though, given the distribution of participants it is not possible to
avoid certain hours entirely. The in-person meeting location follows the 1-1-1 rule as documented in {{RFC8719}}
to rotate between Asia, Europe,  and North America. While the exact time slot used had led to various discussions,
following this 1-1-1 rule to share the pain has/seems to have rough consensus.

# Guidelines for Online Meeting Planning

## Time Zone Selection

This time selection enables to have 2 out of 3 fully online IETF plenary meetings 
during the day from most participants. Basically every full online meeting is for two regions 
of the three regions described in {{!RFC8179}}, roughly speaking, after sunrise or after dinner.
This has the tradeoff that it maps the third region in middle of night. However, that also means
for most participants only one remote meeting per year might
require a significant change to sleep schedules.

The times are also seasonally adjusted to leverage differentials in Daylight
Savings Time. These time slots are as follows, in UTC:

| Name | Times (Northern Summer) | Times (Northern Winter) |
| ---- | ----------------------- | ----------------------- |
| North America Night | 0500-1100 UTC | 0600-1200 UTC |
| Asia Night | 1400-2000 UTC | 1500-2100 UTC |
| Europe Night | 2200-0400 UTC | 2200-0400 UTC |

The intent of rotating between these three slots is to scatter meetings
throughout the course of the global day, to maximize the ease of participants
to occasionally attend regardless of their location and what time of day is
optimal for their schedule.

### Rules for selection

The IETF will select a start time from these three choices based on the past
three meetings. The following table covers all permutations of previous
meetings held in-person in Region A, B, or C; or remotely in the nights of
one of those regions.

| 3 meetings ago | 2 meetings ago | Last Meeting | Online Selection |
| -------------- | -------------- | ------------ | ---------------- |
| Any | Any | In-Person A | A Night |
| Any | Online A Night | Online B Night | C Night |
| Online A Night | In-Person B | Online B Night | C Night |
| In-Person A | In-Person B | Online B Night | A Night |
| In-Person A | In-Person A | Online A Night | see below |
| Online A Night | Online B Night | Online C Night | A Night |

Basically this table follows two rules:
1) When ever a fully online meeting follows and in-person meeting, the online meeting time is used that disadvantages most the participants of the time zone where the in-person meeting was held.
2) If multiple fully online meetings follow each other, the time zone selection should be rotated based on the most recent time zones that the in-person meetings were held in.

The final case occurs in the rare event that back-to-back in-person plenaries
occur in the same region. In this case, find the most recent meeting that was
neither in 'A' (if in person) nor in 'A' night (if remote). If this meeting
was in-person in region 'B', then the next meeting will be in 'B' Night. If it
was remote in 'B' Night, the next meeting will be in 'C' Night.

To initialize this algorithm, IETF 112 is considered as an 'Asia Night'
remote meeting, and IETF 111 is a 'Europe Night' remote meeting.

## Number of Days and Total Hours per Day

Online meetings have converged to run over 5 days with 6-hour meeting days, roughly.
Only, the administrative plenary, which concludes with multiple open mic sessions, is not necessarily time-bounded.

Based on the experience so far, 6 hours of online meetings, with two 30 minutes breaks,
appears to be potentially a natural limited of what is handleable for most participants.
Respectively, the meeting survey after IETF 109 has indicated a high satisfaction with the distribution of sessions
over 5 days but only a medium satisfaction with the
overall length of each day [https://www.ietf.org/blog/ietf108-survey-results-informed-planning/]. 

While there is a possible trade-off between shorter but more days,
a compact and potentially intense meeting was slightly prefer from the beginning by the community.
And, different than for in-person meetings, it was never seen as a necessary option to also utilize time during the 
weekend. So far, it was possible for all meetings to fit the requested number of sessions within 5 days, with the
respective number of parallel tracks (see next section).

While the time during an in-person meeting can be used very intensively, even a compact and full online
schedule does often not prevent day-job duties to occur in parallel.  Therefore, allocating more days can also
make it more difficult for people to join and as such needs to be balanced with the option to distribute load
better over the entirely year by a more regular use of interim meetings.

## Session/Break Length

Session length and the number of parallel tracks are handled similar to in-person meetings,
only that there are less sessions per day to keep the overall meeting day to at roughly 6 hours.
The reduction to three instead of four sessions per day led to the practice of offering chairs only two options for
session length (instead of three), in order to make session scheduling more practical.

At IETF-108, based on an indicated preference of the community, 50 and 100 minute slot were used,
with only 10 minutes breaks, in order to keep the overall day length at 5 hours.
This resulted in many sessions going over time and clearly indicated that only 10 minutes for breaks are not
practical. 

The survey after IETF-109 showed a high satisfaction with 60/120 minute session lengths and 30 minute breaks,
and a significant improvement in satisfaction over IETF-108. [https://www.ietf.org/blog/ietf-109-post-meeting-survey/]

While the option to shorten the breaks was discussed during the later meetings,
a saving of in total 10-20 minutes per day might not balance the need to use the breaks for recreation or 
at least some socialising.

## Number of Parallel Tracks

Fully online meetings are not limited in the number of parallel tracks by the physical restriction of a meeting venue aka
the number of meeting rooms. However, the more parallel tracks there are,
the higher chances are for conflicts. Therefore it is
desirable to balance the requested sessions mostly equally over the available slots and thereby
minimise the number of parallel tracks where possible.

If the number of requested sessions exceeds the number of possible slots with the usual 8 parallel tracks, it
is possible for an online-only meeting to use more tracks. After all, this decision is implicitly made by the working group
chairs requesting a certain number of sessions and length. While realistic planning is desired to avoid running over time,
chairs are still encouraged to request plenary meeting time carefully and use interims where possible and sensible
instead.

## Full vs. limited agenda

The IETF-108 meeting survey asked about the structure of that meeting (full meeting) compared to that of IETF 107,
which hosted only a limited set of session followed by interims in the weeks after. The structure of IETF 108 was
preferred by 82% [https://www.ietf.org/blog/ietf-108-meeting-survey/]. While the limited agenda of IETF-107
could have been a good one-time replacement, the value of cross participation and high active meetings weeks
has been recognised as important for continuous progress (and not only for newly initiated work).

# Experiments

Similar as for in-person meeting, it is desirable to experiment with the meeting structure. Often only practical
experience can answer open questions. It is recommended to not experiment with a larger number of different
aspects at the same time, in order to be able to assess the outcome correctly. It is further recommended to announce any
such experiment in advance, so people adjust to changes and potentially provide feedback.


# Chances and Lessons Learnt

Participation of the most recent online only meetings were rather high and had a quite stable per-country distribution,
even though time zones were rotated. This indicates that online meetings support a more easy and therefore potentially
broader participation than in-person meetings where participation is often fluctuating based on the location.

However, it has also been recognised that the online meeting does not provide an equivalent opportunity to socialize.
The observed slight decrease in submission of new (-00) drafts, while the overall number of draft submission and
productivity seem to stay stable, might also be an indication of the dismiss of these interactions. The increase in interim
meetings potentially compensates for these missing interactions for continuous work (or may even increase
productivity there), but seems to be less adequate to spark new ideas.

None of the data observed so far can, however, be interpreted as showing a significant trend. However, these factors
should be consider for the organization of future online-only meetings in replacement or addition to in-person meetings.


# Acknowledgments
