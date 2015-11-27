# What do we need to launch a first version?

## Authoring Tools

- setup
    - node
    - npm install bpm
    - git config
    - github account

- authoring episodes
    - write episode and meta data (readme.md)
    - write meta data: `bpm init`
        - [ ] current test reads .npmrc. do not.
        - [ ] add more tests
        - [ ] extend readme
        - [x] remove bpm init stuff from bpm
    - embed media
        - video: brainpm-youtube
        - yt liked tag manager
    - quiz
        - markdown extension: brainpm/quiz
        - reveal questions one at a time
        - integrate quiz md parser with episode md parser
        - a way to author per-answer feedback

    - bpm subcommands
        - rename toc to ls
        - bpm ls
            - add command line options to get
                - provided knowledge
                - required knowledge
                - track
                - version
        - bpm info <episode>

    - publishing
        - bpm-bundle
        - bpm-github (aka bpm-publish)

## Learning Environment

- web-player
    - inventory
    - history
    - persistence
    - slick UI
    - [feedback]
    
## Content
    - history
    - UNIX, terminal, shell, command line basics
    - the "social" in social coding
    - HTML/CSS (external)
    - HTTP basics / network stack
        - mime types
        - ETAGs
        - GET, PUT, POST
        - status codes
        - POST body / querystring
    - JS basics
    - node basics
    - simple node backend on heroku (or similar service)
    - project: something multi-user and fun.
