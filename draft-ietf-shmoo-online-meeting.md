---
title: Guidelines for the Organization of Fully Online Meetings
abbrev: Organization Online Meetings
docname: draft-ietf-shmoo-online-meeting-latest
date:
category: info

ipr: trust200902
keyword: Internet-Draft

stand_alone: yes
pi: [sortrefs, symrefs]

author:
  -
    ins: M. Kühlewind
    name: Mirja Kühlewind
    org: Ericsson
    email: mirja.kuehlewind@ericsson.com
  -
    ins: M. Duke
    name: Martin Duke
    org: Google
    email: martin.h.duke@gmail.com


normative:

informative:

  107-FEEDBACK:
    title: "IETF 107 Virtual Meeting Survey Report"
    author:
      - ins: J. Daley
    date: 2020-04-17
    target: "https://www.ietf.org/media/documents/ietf-107-survey-results.pdf"

  108-SURVEY:
    title: "IETF 108 Meeting Survey"
    author:
      - ins: J. Daley
    date: 2020-08-13
    target: "https://www.ietf.org/blog/ietf-108-meeting-survey"

  109-SURVEY:
    title: "IETF 109 Post-Meeting Survey"
    author:
      - ins: J. Daley
    date: 2020-12-07
    target: "https://www.ietf.org/blog/ietf-109-post-meeting-survey/"

  111-SURVEY:
    title: "IETF 111 Post-Meeting Survey"
    author:
      - ins: J. Daley
    date: 2021-08-23
    target: "https://www.ietf.org/blog/ietf-111-post-meeting-survey/"

  112-EXPERIMENT:
    title: "IETF 112 Plenary Experiment Evaluation"
    author:
      - name: IESG
    date: 2022-02-04
    target: "https://www.ietf.org/blog/ietf112-plenary-experiment-evaluation/"

  INTERIM-SCHEDULE:
    title: "Post-IETF-107 Recommended Virtual Interim Schedule"
    author:
      - ins:  A. Cooper
    date: 2020-03-13
    target: "https://mailarchive.ietf.org/arch/msg/wgchairs/l382SqKVVHoTzFw9kIYl2boM6_c/"


--- abstract

This document provides guidelines for the planning and organization of fully
online meetings, regarding the number, length, and composition of sessions on
the meeting agenda. These guidelines are based on the experience with online
meetings during the COVID-19 pandemic in 2020 and 2021.

--- middle

# Introduction

In 2020, the COVID-19 pandemic forced the IETF to convert all its plenary meetings
to online-only events. This document records the experience gained by holding
plenary meetings fully online and proposes guidelines based on this experience.
In general, participant surveys indicate satisfaction with the organization of
these meetings.

Although these guidelines reflect lessons learned in 2020 and 2021, the IETF is
encouraged to continue to experiment with the format and agenda of fully online
meetings, using this document as a baseline.

Hybrid meetings (meaning meetings that have large remote participation but also
onsite participation) are out of scope. However, some of the experience gained
from fully online meetings might also provide input for decisions regarding the
organization of hybrid meetings.

## Requirements Language

{::boilerplate bcp14-tagged}

This document uses the term "plenary meeting" for the whole IETF meeting that
covers the IETF meeting week; this term is used to distinguish the plenary meeting
from other IETF meetings like "interim meetings".
The term "administrative plenary" is used for the respective session
during the IETF meeting week that is usually hosted on Wednesday.

# Some History

When the WHO declared a world-wide pandemic in March 2020, the IETF canceled its
plenary meeting and organized an online replacement in less than two weeks. For
this first online-only meeting, the agenda was reduced to a set of sessions that
benefitted most from cross-area participation, like BoFs, first-time meetings of
new working groups, and dispatch sessions. It also included the administrative
plenary to preserve the official hand-over procedures that occur at the March
meeting, as described in {{?RFC8713}}.

With a reduced agenda, the meeting format was 2 sessions (about 4 hours) per day
with a maximum of two parallel tracks. Other working group meetings were
scheduled as interims over the following six weeks. The IESG published a
purely advisory recommended schedule {{INTERIM-SCHEDULE}} to reduce conflicts
among those interims.

While satisfation was high right after the meetinng {{107-FEEDBACK}}, participants
later indicated in mailing discussion that the period of intensive interims had a
greater impact on their calendar than a single plenary meeting week, and in some
meeting. Those interims tended to occur at times convenient for the bulk
of participants, which was convenient for most but could exclude those in less
common time zones.

For the remainder of 2020 and 2021, the online schedule was switched back to be
similar to an in-person meeting (1-2 hour slots and 8-9 parallel tracks).
However, each day was limited to 5-6 hours in recognition that remote
participation is more tiring.

All fully online meetings followed the time zone of the planned in-person
meeting location. As a six-hour agenda has some flexibility regarding the start
time while still fitting within a previously used 8-hour in-person agenda, the start
time was approximately noon, with adjustments of an hour or so to mitigate the
impact of early morning hours in time zones with many participants. As selection
of in-person meeting sites was consistent with the 1-1-1 guideline as documented
in {{?RFC8719}}, this approach was intended to share the burden across all common
geographies roughly equally.

# Guidelines for Online Meeting Planning

## Time Zone Selection

The following algorithm was not used in 2020 or 2021, but enables most
participants to avoid late-night sessions in 2 out of every 3 fully online IETF
plenary meetings. Basically, every full online meeting is for two regions of the
three regions described in {{!RFC8179}}, with one being roughly after sunrise
and the other after dinner. This has the tradeoff that the third region is in
the middle of night.

The times are also seasonally adjusted to leverage differentials in Daylight
Savings Time. These time slots are as follows, in UTC:

| Name | Times (Northern Summer) | Times (Northern Winter) |
| ---- | ----------------------- | ----------------------- |
| North America Night | 0500-1100 UTC | 0600-1200 UTC |
| Asia Night | 1300-1900 UTC | 1400-2000 UTC |
| Europe Night | 2200-0400 UTC | 2200-0400 UTC |

The intent of rotating between these three slots is to scatter meetings
throughout the course of the global day, to maximize the ease of participants
to occasionally attend regardless of their location and what time of day is
optimal for their schedule.

### Guidelines for selection

The IETF SHOULD select a start time from these three choices based on the past
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

This table follows two basic guidelines:
1) Whenever a fully online meeting follows an in-person meeting, the online
meeting time is used that most disadvantages most the participants of the time zone
where the in-person meeting was held.
2) If multiple fully online meetings follow each other, the time zone selection
should be rotated based on the most recent time zones that the in-person
meetings were held in.

The final case occurs in the rare event that back-to-back in-person plenary meetings
occur in the same region. In this case, find the most recent meeting that was
neither in 'A' (if in-person) nor in 'A' night (if fully online). If this meeting
was in-person in region 'B', then the next meeting should be in 'B' Night. If it
was remote in 'B' Night, the next meeting should be in 'C' Night.

## Number of Days and Total Hours per Day

By 2021, fully online meetings were consistently over 5 days with roughly 6-hour
meeting days. The day with the administrative plenary, which concludes with
multiple open mic sessions, sometimes exceeded this limit.

Six hours of online meetings, with two 30-minute breaks, was a compromise
between the physical limits of attending an online meeting in an inconvenient
time zone, and the demand for many sessions with a manageable number of
conflicts. The IETF 109 feedback {{109-SURVEY}} indicated broad satisfaction
with a 5-day meeting but only medium satisfaction with the overall length of
each day.

The IETF did not seriously consider extending sessions into the weekend before
or after the main meeting week, although the Hackathon occupied the entire week
before (see {{?RFC9311}}).

## Session/Break Length

For fully online meetings there are typically fewer sessions per day than for
in-person meetings, to keep the overall meeting day to roughly 6 hours.
With fewer sessions, chairs were offered only two options for session length
(instead of three).

IETF-108, based on an indicated preference of the community, scheduled 50- and
100-minute slots, with 10-minute breaks, in order to keep the overall day length
at 5 hours. This resulted in many sessions going over time, which indicated that
10 minutes for breaks is not practical.

The survey after IETF-109 {{109-SURVEY}} showed high satisfaction with 60/120-minute
session lengths and 30-minute breaks, and a significant improvement in
satisfaction over IETF-108.

The longer breaks, while extending the day, provided adequate time for "hallway"
conversations using online tools, exercise, and meals.

## Number of Parallel Tracks {#tracks}

In-person meetings are limited in the number of parallel tracks by the number of
meeting rooms, but online meetings are not. However, more parallel tracks
increases the number of possible conflicts.

If the total number of requested sessions exceeds the capacity of the usual 8
parallel tracks, it is possible for a fully online meeting to simply use more
tracks. If the number and length of meeting days is seen as fixed, this decision
is implicitly made by the working group chairs requesting a certain number of
sessions and length.

IETF-111 used 9 parallel tracks for some of the sessions, and experienced
slightly more conflicts in the formal scheduling process, though there was no
statistically significant increase in dissatisfaction about conflicts in the
survey {{111-SURVEY}}.

The IESG encouraged working group chairs to limit their session requests and use
interim meetings aggressively for focused work.

# Additional Considerations and Recommendations

## Full vs. limited agenda (and interim meetings) {#full-limited}

The IETF-108 meeting survey {{108-SURVEY}} asked about the structure of that
meeting (full meeting) compared to that of IETF 107, which hosted only a limited
set of session followed by interims in the weeks after. The structure of IETF
108 was preferred by 82%. Respondents valued cross-participation and an
intensive meeting week for maintaining project momentum.

Furthermore, a well-defined meeting time, rather than spreading many interims
over the whole year, can make deconflicting with other non-IETF meetings easier.

However, interim meetings can also help to reduce scheduling conflicts during an
IETF week and allow for a more optimal time slot for the key participants. While
interim meetings are less likely to attract people with casual interest, they
provide a good opportunity for the most active participants of a group to have
detailed technical discussions and solve recorded issues efficiently.

## Flexibility of time usage

This document recommends further experiments with reducing conflicts by
leveraging the increased flexibility of the online format.

An in-person meeting must fit all sessions into an acceptable length for
international travel (usually roughly a week), but online meetings do not have
that constraint.

Therefore, it would be possible to keep most regular working group sessions
within the usual five main meeting days but have some of the more conflicted
sessions in other dedicated time slots. As the Hackathon for fully online only
meetings is usually held in the week before the online plenary meeting
{{RFC9311}}, that week is already a highly active week for many IETF
participants and might provide an opportunity to schedule a few selected
sessions.

This might work especially well for sessions that are of high interest to a
large part of community, such as BoFs and dispatch meetings, and therefore hard
to schedule during the main IETF week.

At IETF 112, the IESG ran an experiment where the administrative plenary was
scheduled on the Wednesday before the official session week. The experiment
report {{112-EXPERIMENT}} found that it led to a reduction in scheduling
conflicts but also a slight drop attendance of the administrative plenary, partly
due to insufficient awareness.

## Inclusivity and Socializing

Participation in the fully online meetings in 2021 was high and had a stable
per-country distribution, even though time zones were rotated. This indicates
that online meetings support a more consistent geographic distribution of
participants than in-person meetings, where participation often fluctuates based
on the location.

However, online meetings do not provide an equivalent opportunity to socialize.
Despite significant investment in tools to foster hallway conversations, many
did not use those tools, whether due to ignorance of them, dislike of the tools,
or a preference for the amusements of home (including sleep) over hallway
interactions.

There was a slight decrease in submission of new (-00) drafts during 2020 and
2021, although the overall number of draft submissions remained stable, which
might result from the loss of these interactions. Informal conversations might
be important to inspire new work.

## Experiments

This document RECOMMENDS further experiments with the meeting structure. Often,
only practical experience can answer open questions. A given meeting SHOULD only
experiment with one major change at a time in order to be able to assess the outcome correctly.
Furthermore, the IESG SHOULD announce any such experiment in advance, so people
can adjust to changes and potentially provide feedback.

# Acknowledgments

Thanks to Brian Carpenter, Lars Eggert, Toreless Eckert, Charles Eckel, Jason
Livingood, and Sanjeev Gupta for their review and many from more for their
input and suggestions on the time zone discussion!
