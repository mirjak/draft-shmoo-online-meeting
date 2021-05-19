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
to rotate between Asia, Europe,  and North America. While the exact time slot used had let to various discussions,
following this 1-1-1 rule to share the pain has/seems to have rough consensus.

# Guidelines for Online Meeting Planning

## Time Zone Selection

All fully online IETF plenary meetings begin at 0500 ("Asia"), 1200 ("Europe"), or 2100 ("North America") UTC. The names
are not meant to imply that all participants in a given region will find the times convenient given their personal
schedules, but are useful for the selection rules below. These location names are consistent with the venue
selection criteria in {{?RFC8719}}.

The selected slots have been proposed to minimize inconvenience while not excessively penalizing any time zone.
Effectively, there is an early morning and a late afternoon meeting for two of the three regions in
each slot. E.g. the "Asia" 0500 UTC slot would be 0600 CET (early morning) and 1300 China Standard Time (afternoon). Since fully
online meeting days are expected to be shorter then in-person meetings, this slot is roughly within the "usual" working hours
of both regions.

The intent of rotating between these three slots is to scatter meetings throughout the course of the global day, to maximize the ease
of participants to occasionally attend regardless of their location and what time of day is optimal for their schedule.

### Rules for selection

The IESG will select a start time from these three choices according the following rules, applied in order. The IESG MAY deviate from
these selection criteria, and the time slots listed above, after consultation with the wider community in non-emergency situations.

1. Eliminate all regions that had an in-person meeting in that calendar year. If one region remains, select the time
slot mapped to that region.

2. Eliminate all regions that have a planned in-person meeting that calendar year. If one region remains, select the
time slot mapped to that region.

3. Select the region that has least recently had an fully online IETF plenary in its slot. For the pandemic cancellations
of 2020- 2021, the original host cities are used to determine the host region. Therefore, at the time of writing the
most recent selections are Asia in November 2020, Europe in March 2021, and North America in July 2021.


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
The reduction to three instead of four sessions per day let to the practice of offering chairs only two options for
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
meetings potentially compensates for these missing interactions for continuous work (or may even increases 
productivity there), but seems to be less adequate to spark new ideas.

None of the data observed so far can, however, be interpreted as showing a significant trend. However, these factors
should be consider for the organization of future online-only meetings in replacement or addition to in-person meetings.


# Acknowledgments
