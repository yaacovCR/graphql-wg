<!--

# How to join (copied directly from /JoiningAMeeting.md)

Hello! You're welcome to join our working group meeting and add to the agenda by
following these three steps:

1.  Add your name to the list of attendees (in alphabetical order).

    - To respect meeting size, attendees should be relevant to the agenda. That
      means we expect most who join the meeting to participate in discussion. If
      you'd rather just watch, check out our [YouTube][].

    - Please include the organization (or project) you represent, and the
      location (including [country code][]) you expect to be located in during
      the meeting.

    - If you're willing to help take notes, add "✏️" after your name (eg. Ada
      Lovelace ✏). This is hugely helpful!

2.  If relevant, add your topic to the agenda (sorted by expected time).

    - Every agenda item has four parts: 1) the topic, 2) an expected time
      constraint, 3) who's leading the discussion, and 4) a list of any relevant
      links (RFC docs, issues, PRs, presentations, etc). Follow the format of
      existing agenda items.

    - Know what you want to get out of the agenda topic - what feedback do you
      need? What questions do you need answered? Are you looking for consensus
      or just directional feedback?

    - If your topic is a new proposal it's likely an ["RFC 0"][rfc stages]. The
      barrier of entry for documenting new proposals is intentionally low,
      writing a few sentences about the problem you're trying to solve and the
      rough shape of your proposed solution is normally sufficient.

      You can create a link for this:

      - As an issue against the graphql-wg repo.
      - As a GitHub discussion in the graphql-wg repo.
      - As an RFC document into the rfcs/ folder of the graphql-wg repo.

3.  Review our guidelines and agree to our Spec Membership & CLA.

    - Review and understand our Spec Membership Agreement, Participation &
      Contribution Guidelines, and Code of Conduct. You'll find links to these
      in the first agenda item of every meeting.

    - If this is your first time, our bot will comment on your Pull Request with
      a link to our Spec Membership & CLA. Please follow along and agree before
      your PR is merged.

      Your organization may sign this for all of its members. To set this up,
      please ask operations@graphql.org.

PLEASE TAKE NOTE:

- By joining this meeting you must agree to the Specification Membership
  Agreement and Code of Conduct.

- Meetings are recorded and made available on [YouTube][], by joining you
  consent to being recorded.

[youtube]: https://www.youtube.com/channel/UCERcwLeheOXp_u61jEXxHMA
[country code]:
  https://en.wikipedia.org/wiki/List_of_ISO_3166_country_codes#Current_ISO_3166_country_codes
[rfc stages]:
  https://github.com/graphql/graphql-spec/blob/main/CONTRIBUTING.md#rfc-contribution-stages


-->

| This is an open meeting: To attend, read [JoiningAMeeting.md][] then edit and PR this file. (Edit: ✎ above, or press "e") |
| ---------------------------------------------------------------------------------------- |

# GraphQL WG — April 2024 (Primary)

The GraphQL Working Group meets regularly to discuss changes to the
[GraphQL Specification][] and other core GraphQL projects. This is an open
meeting in which anyone in the GraphQL community may attend.

This is the primary monthly meeting, which typically meets on the first Thursday
of the month. In the case we have additional agenda items or follow ups, we also
hold additional secondary meetings later in the month.

- **Date & Time**: [April 4, 2024, 10:30 AM – 12:00 PM PDT](https://www.timeanddate.com/worldclock/converter.html?iso=20240404T173000&p1=224&p2=179&p3=136&p4=268&p5=367&p6=438&p7=248&p8=240)
  - View the [calendar][], or subscribe ([Google Calendar][], [ical file][]).
  - _Please Note:_ The date or time may change. Please check this agenda the
    week of the meeting to confirm. While we try to keep all calendars accurate,
    this agenda document is the source of truth.
- **Video Conference Link**: https://zoom.us/j/593263740
  - _Password:_ graphqlwg
- **Live Notes**: [Live Notes][]

[calendar]: https://calendar.google.com/calendar/embed?src=linuxfoundation.org_ik79t9uuj2p32i3r203dgv5mo8%40group.calendar.google.com
[google calendar]: https://calendar.google.com/calendar?cid=bGludXhmb3VuZGF0aW9uLm9yZ19pazc5dDl1dWoycDMyaTNyMjAzZGd2NW1vOEBncm91cC5jYWxlbmRhci5nb29nbGUuY29t
[ical file]: https://calendar.google.com/calendar/ical/linuxfoundation.org_ik79t9uuj2p32i3r203dgv5mo8%40group.calendar.google.com/public/basic.ics
[graphql specification]: https://github.com/graphql/graphql-spec
[JoiningAMeeting.md]: https://github.com/graphql/graphql-wg/blob/main/JoiningAMeeting.md
[live notes]: https://docs.google.com/document/d/1q-sT4k8-c0tcDYJ8CxPZkJ8UY4Nhk3HbKsRxosu_7YE/edit?usp=sharing

## Attendees

<!-- prettier-ignore -->
| Name             | GitHub        | Organization       | Location              |
| :--------------- | :------------ | :----------------- | :-------------------- |
| Lee Byron (Host) | @leebyron     | GraphQL Foundation | San Francisco, CA, US |
| Martin Bonnin    | @martinbonnin | Apollo             | Paris, FR             |
| Benjie Gillam    | @benjie       | Graphile           | Chandler's Ford, UK   |
| Michael Staib    | @michaelstaib | ChilliCream        | Zurich, CH            |
| Jeff Auriemma    | @bignimbus    | Apollo             | Monroe, CT, US        |
| Rob Richard      | @robrichard   | 1stDibs            | Jersey City, NJ, US   |
| Uri Goldshtein   | @urigo        | The Guild          | Tel Aviv, IL          |

## Agenda

1. Agree to Membership Agreement, Participation & Contribution Guidelines and Code of Conduct (1m, Host)
   - [Specification Membership Agreement](https://github.com/graphql/foundation)
   - [Participation Guidelines](https://github.com/graphql/graphql-wg#participation-guidelines)
   - [Contribution Guide](https://github.com/graphql/graphql-spec/blob/main/CONTRIBUTING.md)
   - [Code of Conduct](https://github.com/graphql/foundation/blob/master/CODE-OF-CONDUCT.md)
1. Introduction of attendees (5m, Host)
1. Determine volunteers for note taking (1m, Host)
1. Review agenda (2m, Host)
1. Review prior secondary meetings (5m, Host)
   - [GraphQL WG — March 2024 (Secondary, APAC)](https://github.com/graphql/graphql-wg/blob/main/agendas/2024/03-Mar/13-wg-secondary-apac.md)
   - [GraphQL WG — March 2024 (Secondary, EU)](https://github.com/graphql/graphql-wg/blob/main/agendas/2024/03-Mar/21-wg-secondary-eu.md)
1. Review previous meeting's action items (5m, Host)
   - [Ready for review](https://github.com/graphql/graphql-wg/issues?q=is%3Aissue+is%3Aopen+label%3A%22Ready+for+review+%F0%9F%99%8C%22+sort%3Aupdated-desc)
   - [All open action items (by last update)](https://github.com/graphql/graphql-wg/issues?q=is%3Aissue+is%3Aopen+label%3A%22Action+item+%3Aclapper%3A%22+sort%3Aupdated-desc)
   - [All open action items (by meeting)](https://github.com/graphql/graphql-wg/projects?query=is%3Aopen+sort%3Aname-asc)
1. Note: [ID _must_ be serialized as String](https://github.com/graphql/graphql-spec/pull/1086) was merged (1m, Benjie)
1. strict error paths (5m, Martin)
   - Are we ready to merge https://github.com/graphql/graphql-spec/pull/1073?
1. Define 'selection set' (5m, Benjie)
   - [Editorial PR](https://github.com/graphql/graphql-spec/pull/1032)
   - Already 4 WG member approvals; aim: merge
1. Ordering of schema elements (10m, Benjie)
   - [RFC](https://github.com/graphql/graphql-spec/pull/1063)
   - Question: should fields, input fields, arguments be defined as an "ordered map" rather than an "ordered set" (previously a "list")?
1. Request `extensions` (10m, Benjie)
   - [RFC](https://github.com/graphql/graphql-spec/pull/976)
   - Previously: [2024-03-07](https://github.com/graphql/graphql-wg/blob/main/notes/2024/2024-03.md#add-extensions-to-request-5m-benjie), [2022-09-01](https://github.com/graphql/graphql-wg/blob/623a7bc464406509e0cf41c847e4e4322d577764/notes/2022/2022-09-01.md#specifying-extensions-property-on-requests-10m-benjie) ([video](https://youtu.be/MEi1u6L__Ck?list=PLP1igyLx8foH30_sDnEZnxV_8pYW3SDtb&t=3225))
