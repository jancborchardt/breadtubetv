---
title: BreadTube.tv Mission
type: page
---

[BreadTube.tv](https://breadtube.tv) is the collaborative effort of the content and development community working together via [github/BreadTubeTV](/github).

BreadTube.tv seaks to bring together Creators, Subscribers, Moderators, Developers, Designers, Coordinators who are involved in the [r/BreadTube](/reddit).

The Website is a resource for discovering and sharing BreadTube content, it also serves as a push for us to developer better tooling and more automation of the concept for other communities, creators, and moderators.

## Workflows

### Suggesting a Channel

{{<mermaid align="left">}}
  graph TB;
    A[Channel Form] -->|User Submits| B[Discord Notice]
      B -->|Developer Reads| BAKE[Bake Import]
      BAKE -->|Pull Request| GH[Github]
      GH --> C{On r/BreadTube?}
      C -->|Yes| D[Needs Review]
      C -->|No| E[Discussion]
      D -->|Reviewed| F(Ready to Merge)
      F -->|Merged| G(Live on BreadTube.tv)
      E -->|Discussed| H{Mergeable?}
      H --> D
    click A "/channels/new"
    click B "/discord"
    click BAKE "https://github.com/breadtubetv/bake"
    click GH "https://github.com/breadtubetv/breadtubetv"
    click C "https://www.reddit.com/r/BreadTube/search?q=contrapoints&restrict_sr=1"
    click D "https://github.com/breadtubetv/breadtubetv/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Aopen+label%3A%22needs+review%22+"
    click E "https://github.com/breadtubetv/breadtubetv/pulls?q=is%3Apr+is%3Aopen+label%3ADiscussion"
    click G "https://breadtube.tv/channels"
{{< /mermaid >}}

## Features

- ### HomePage
  - [BreadTube.tv](https://breadtube.tv)
  - Lists [r/BreadTube](https://www.reddit.com/r/breadtube/top/?t=month) Monthly Top

- ### List Channels
  - [BreadTube.tv/channels](https://breadtube.tv/channels)
  - Listed Alphabetically
  - Channels Search
      - [Name #search:contrapoints](https://breadtube.tv/channels#search:contrapoints)
      - [Tag #search:anarchy](https://breadtube.tv/channels#search:anarchy)

- ### Channel Pages
  - Channel Information
    - [BreadTube.tv/contrapoints](https://breadtube.tv/contrapoints)
    - [BreadTube.tv/noncompete](https://breadtube.tv/noncompete)
  - Channel Videos List

- ### Suggest Channel Form
    - [BreadTube.tv/channels/new](https://breadtube.tv/channels/new)

- ### List Playlists
    - [BreadTube.tv/playlists](https://breadtube.tv/playlists)

- ### Playlist Pages
    - [BreadTube.tv/playlists/welcome](https://breadtube.tv/playlists/welcome)

- ### Suggest Playlist Form
    - [BreadTube.tv/playlists/new](https://breadtube.tv/playlists/new)

- ### Manual Form Processing
  - Discord Notified of Submission
  - Human's creates Pull Request
  - Discord Notified of Pull Request

## In Development Features

### Content Management Interface

#### [Netlify CMS](https://www.netlifycms.org/)

### Channel Link to r/BreadTube Search

### List of All Videos

### PearTube Sources Integration

- ### Videos have their own page, eg:
  - [BreadTube.tv/contrapoints/theaesthetic/](https://deploy-preview-198--breadtubetv.netlify.com/contrapoints/theaesthetic/)

- ### Video Embedded on Page
  - YouTube Videos
  - QueerTube Videos
  - Other Sources Configurable in the future

- ### iFrame Video Playback


#### [Preview](https://deploy-preview-198--breadtubetv.netlify.com/contrapoints/theaesthetic/)
#### [GitHub#198](https://github.com/breadtubetv/breadtubetv/pull/198)

## Future Features

- ### Live TwitchTV Notices

- ### Suggest Video Form

- ### Edit Channel Form

- ### Edit Playlist Form

- ### Automated Processing
  - Form Processing (bot creates pull request)
  - YouTube Video processing
  - YouTube Channel processing
  - YouTube Playlist processing

- ### Progressive web app (PWA)

- ### Native web apps loading PWA (iOS & Android)

- ### Live Notices
  - YouTube
  - Facebook
  - Instagram

The ultimate possibilities for this system are dependent on the needs of the BreadTube community, this infrastructure being developed serves as a source of inspiration for the development of future tooling to support the movement.

## Values

Our values as a development team are those of any other self organizing community, those of the conquest of bread itself. Our utility and existence to the movement is dependent on us being informed, understanding, and empathetic of the needs of the community and to respond by developing them the things that can make them flourish.

We do not consider ourselves to be the single instance of this mission, our collaboration is entirely voluntary and non binding, what we learn and achieve together on the projects we embark on will serve ourselves and further causes throughout time in unknowing ways.

## Technology

This website is not build on Wordpress or any other database dependent content management system

This inherently creates a barrier of entry that we are working to minimize alongside many other developers

## Provide Feedback

### [Discord](/discord)

Definitely the easiest way to get to us is at [BreadTube.tv/Discord](/discord)
